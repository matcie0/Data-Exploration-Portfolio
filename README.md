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


## Sprawozdanie 3: Klasyfikacja Nadzorowana 

Projekt skupia się na praktycznym zastosowaniu algorytmów klasyfikacji oraz zaawansowanych metodach oceny ich dokładności. Głównym celem było porównanie skuteczności modeli w rozpoznawaniu wzorców oraz walka z problemem maskowania klas.

**[Pobierz pełne Sprawozdanie w PDF](./Supervised-Learning-Classification/Sprawozdanie3.pdf)**

#### Zakres analizy:
* **Rozszerzona Przestrzeń Cech - Zbiór Iris (Autor: [Dawid](https://github.com/DawidSkowronski)):**
  * Konstrukcja klasyfikatora opartego na regresji liniowej.
  * Konstrukcja modelu liniowego dla rozszerzonej przestrzeni cech.

* **Modelowanie i Optymalizacja - Zbiór Vehicle (Autorzy: Mateusz Cieślak i [Dawid](https://github.com/DawidSkowronski)):**
  * Porównanie trzech metod: **k-NN**, **Naiwny Klasyfikator Bayesowski** oraz **Drzewa Klasyfikacyjne**.
  * Próba zwiększenia dokładności poprzez zastosowanie różnych parametrów i podzbiorów cech.
  
## Sprawozdanie 4: Zaawansowane Metody Klasyfikacji (Ensemble Learning, SVM) i Analiza Skupień

Ostatni etap cyklu projektowego, skupiający się na najskuteczniejszych algorytmach współczesnego Data Mining. Projekt łączy potęgę modeli zespołowych z precyzją maszyn wektorów nośnych oraz eksploracją struktur ukrytych przy pomocy klasteryzacji.

**[Pobierz pełne Sprawozdanie w PDF](./Ensemble-Learning-SVM-Clustering/Sprawozdanie4.pdf)**

#### Zakres analizy:

* **Zadanie 1: Zaawansowana Klasyfikacja (Supervised Learning) (Autor: Mateusz Cieślak):**
  * **Ensemble Learning:** Implementacja i porównanie metod zespołowych: **Bagging** oraz **Random Forest**. Analiza stabilności błędu OOB (Out-of-Bag) w zależności od liczby drzew oraz badanie ważności cech (Feature Importance).
  * **Support Vector Machines (SVM):** Optymalizacja klasyfikatora SVM przy użyciu różnych funkcji jądrowych (liniowej, wielomianowej, radialnej). 
  * **Tuning:** Wykorzystanie procedury *Grid Search* do znalezienia optymalnych parametrów.

* **Zadanie 2: Analiza Skupień (Unsupervised Learning) (Autorzy: [Dawid](https://github.com/DawidSkowronski) i Mateusz Cieślak):**
  * **Algorytmy Grupujące:** Praktyczne zastosowanie metod **K-means** oraz **PAM** (Partitioning Around Medoids).
  * **Algorytmy Hierarchiczne:** Analiza aglomeracyjna **AGNES** z wykorzystaniem różnych strategii łączenia (Single, Complete, Average Linkage) oraz wizualizacja dendrogramów.
  * **Walidacja i Optymalizacja:** Wybór optymalnej liczby klastrów (K=3) przy użyciu statystyki **Gap**, wskaźnika **Silhouette** oraz reguły łokcia. Ocena stabilności grupowania (miary APN, AD, ADM) i interpretacja cech wyróżniających poszczególne klastry.


#### Narzędzia:
`R`, `RMarkdown`, `randomForest`, `e1071` (SVM), `cluster` (PAM/AGNES), `clValid` (walidacja stabilności), `factoextra` (wizualizacja PCA i klastrów), `NbClust`,
`caret` (walidacja krzyżowa, bootstrap .632+), `rpart` (drzewa), `cmdscale` (MDS), `prcomp` (PCA), `plotly`, `ggplot2`, `dplyr`
