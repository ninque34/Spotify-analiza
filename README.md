# Spotify-analiza
(Spotify Premium Prediction)

## Opis projektu

Projekt analizuje dane użytkowników Spotify oraz przewiduje, czy użytkownik korzysta z płatnej subskrypcji Spotify.

Problem został potraktowany jako klasyfikacja binarna:
- 0 → Free
- 1 → Premium / Student / Family

## W projekcie wykorzystano
- pandas
- matplotlib
- scikit-learn

## Zastosowane modele
- Logistic Regression
- Random Forest
  
## Analiza obejmuje
- czyszczenie danych,
- analizę brakujących danych,
- wizualizację danych,
- przygotowanie danych do machine learning,
- porównanie modeli klasyfikacyjnych.

## Ocena modeli
Modele zostały ocenione przy użyciu:
- classification_report
- F1-score

Oba modele osiągnęły bardzo wysokie i podobne wyniki (F1-score ~1.00), co wskazuje, że problem klasyfikacji jest stosunkowo łatwy dla tego zbioru danych.
Nie zaobserwowano istotnej przewagi jednego modelu nad drugim - oba modele osiągają porównywalną skuteczność.
