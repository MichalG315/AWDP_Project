# Analiza światowego zużycia energii

To repozytorium zawiera projekt analizy danych oparty na zbiorze danych **World Energy Consumption** z Kaggle, pochodzącym ze zbioru _Energy_ utrzymywanego przez Our World in Data.

## Opis projektu

Celem tego projektu jest zbadanie przekrojowe krajów pod względem zużycia energii, miksu energetycznego oraz powiązanych wskaźników w wybranym roku badawczym.  
Korzystając ze zbioru danych, projekt analizuje, jak całkowite zużycie energii oraz udział różnych źródeł energii (paliwa kopalne vs. odnawialne źródła energii) rozkładają się w poszczególnych krajach.

To repozytorium stanowi projekt końcowy na kurs AWDP.

## Zbiór danych

Projekt wykorzystuje zbiór danych **Energy** utrzymywany przez Our World in Data, udostępniony na Kaggle pod nazwą:

> World Energy Consumption – Energy Consumption and Mix dataset by Our World in Data

Strona Kaggle (źródło danych):

- [https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption](https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption)

Najważniejsze cechy:

- Roczne dane na poziomie globalnym, regionalnym i krajowym.
- Wskaźniki dotyczące pierwotnego zużycia energii, zużycia per capita, miksu energetycznego, miksu energii elektrycznej oraz produkcji paliw kopalnych.
- Główny plik danych `owid-energy-data.csv` zawierający 130 kolumn.

## Pytania

Projekt koncentruje się na takich pytaniach jak:

- Jak miks energetyczny różni się pomiędzy wybranymi krajami?
- Jak zużycie energii per capita różni się pomiędzy krajami o wysokich i niskich dochodach?
- Jaka jest zależność pomiędzy zużyciem energii na osobę a rozwojem gospodarczym?

## Metody i narzędzia

Analiza opiera się na typowym workflow stosowanym w data science:

- **Pozyskiwanie danych** – pobranie zbioru danych z Kaggle i załadowanie go do środowiska analitycznego.
- **Czyszczenie i wstępne przetwarzanie danych** – obsługa brakujących wartości, wybór istotnych zmiennych oraz filtrowanie danych do interesującego zakresu czasowego i krajów.
- **Eksploracyjna analiza danych** – statystyki opisowe oraz porównania między krajami.
- **Wizualizacja** – wykresy przedstawiające różnice w miksie energetycznym.

Wykorzystane technologie:

- Python (`pandas`, `NumPy`, `Matplotlib`, `Seaborn` / `Plotly`)
- Jupyter Notebook
- Git i GitHub
