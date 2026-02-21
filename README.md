# Data-Mining-Projects
Repozytorium zawiera 4 kompleksowe sprawozdania analityczne przygotowane w parze podczas kursu Eksploracja Danych

## Sprawozdanie 1: Analiza Churn i Profilowanie Klienta (Telco Customer Churn)

Kompleksowa analiza eksploracyjna (EDA) zbioru danych zawierającego ponad 7000 rekordów firmy telekomunikacyjnej. Projekt koncentruje się na identyfikacji wzorców zachowań klientów rezygnujących z usług oraz optymalizacji strategii utrzymania klienta.

**[Pobierz pełne Sprawozdanie w PDF](./Churn-Analysis/Sprawozdanie1.pdf)**

#### Zakres analizy:
* **Analiza opisowa (Autor: [Dawid](https://github.com/DawidSkowronski)):** 
  * Opracowanie statystyk sumarycznych oraz identyfikacja braków danych (NA).
  * Analiza rozkładów zmiennych ilościowych (tenure, MonthlyCharges) oraz jakościowych.
  * Wykorzystanie wykresów pudełkowych do badania zależności między stażem a typem kontraktu.

* **Analiza opisowa z podziałem na grupy (Autor: Mateusz Cieślak):**
  * **Segmentacja Churn:** Porównanie gęstości empirycznych (estymatory jądrowe) dla grup lojalnych i nielojalnych.
  * **Wykresy Mozaikowe:** Analiza wpływu zmiennych kategorycznych (metoda płatności, typ umowy, technologia światłowodowa) na wskaźnik rezygnacji.
  * **Analiza Trendów Liniowych:** Badanie korelacji między stażem a przychodem całkowitym z podziałem na status klienta.


## Sprawozdanie 2: Redukcja Wymiarów i Analiza Składowych Głównych (MDS & PCA)

Projekt koncentruje się na zaawansowanych metodach uczenia nienadzorowanego, mających na celu uproszczenie złożonych zbiorów danych przy zachowaniu kluczowych informacji statystycznych. Analiza obejmuje trzy zróżnicowane case studies: od biologii (Iris) po globalną jakość życia (City Quality of Life) i historię (Titanic).

**[Pobierz pełne Sprawozdanie w PDF](./Unsupervised-Learning-MDS-PCA/Sprawozdanie2.pdf)**

####  Zakres analizy:
* **Dyskretyzacja Nienadzorowana - Zbiór Iris (Autor: [Dawid](https://github.com/DawidSkowronski)):**
  * Porównanie skuteczności metod: Equal Width, Equal Frequency, K-means oraz przedziałów manualnych.
  * Ocena zdolności dyskryminacyjnej cech biologicznych za pomocą współczynników zgodności.

* **Analiza Głównych Składowych (PCA) - City Quality of Life (Autor: Mateusz Cieślak):**
  * Redukcja 20 zmiennych opisujących jakość życia w 266 miastach do kluczowych wymiarów (PC1, PC2).
  * Interpretacja składowych głównych PC1 i PC2.
  * Ciekawe obserwacje i interpretacja wartości odstających.
  
* **Skalowanie Wielowymiarowe (MDS) - Case Study: Titanic (Autor: [Dawid](https://github.com/DawidSkowronski)):**
  * Zastosowanie algorytmu MDS (Multi-Dimensional Scaling) do wizualizacji struktury pasażerów w przestrzeni 2D i 3D.
  * Mapowanie macierzy niepodobieństwa pozwoliło na klarowną separację grup (płeć, klasa biletu) oraz weryfikację ich wpływu na szansę przeżycia katastrofy.
  * Wykorzystanie wykresów Sheparda i kryterium STRESS*do oceny jakości odwzorowania odległości.



####  Narzędzia:
`cmdscale` (MDS), `prcomp` (PCA), `plotly`
`R`, `ggplot2`, `dplyr`, `RMarkdown`
