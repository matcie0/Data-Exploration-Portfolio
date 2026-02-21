# Data-Exploration-Portfolio
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


#### Narzędzia:
`R`, `ggplot2`, `dplyr`, `RMarkdown`
