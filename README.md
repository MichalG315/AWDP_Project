# Analiza światowego zużycia energii

To repozytorium zawiera projekt analizy danych oparty na zbiorze danych **World Energy Consumption** z Kaggle, pochodzącym ze zbioru *Energy* utrzymywanego przez Our World in Data.

## Opis projektu

Celem tego projektu jest zbadanie trendów krajowych w zużyciu energii, miksie energetycznym oraz powiązanych wskaźnikach na przestrzeni czasu.  
Korzystając ze zbioru danych, projekt analizuje, jak całkowite zużycie energii oraz udział różnych źródeł energii (paliwa kopalne vs. odnawialne źródła energii) zmieniały się w poszczególnych krajach.

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
- Jak globalne zużycie energii pierwotnej zmieniało się na przestrzeni czasu i które źródła energii napędzały te zmiany?
- Jak miks energetyczny (odnawialne źródła energii vs. paliwa kopalne) różni się pomiędzy wybranymi krajami?
- Które kraje zwiększyły udział energii odnawialnej w swoim miksie energetycznym i jak szybko przebiegała ta transformacja?
- Jak zużycie energii per capita różni się pomiędzy krajami o wysokich i niskich dochodach?
- Jaka jest zależność pomiędzy zużyciem energii a rozwojem gospodarczym (np. PKB per capita)?

## Metody i narzędzia

Analiza opiera się na typowym workflow stosowanym w data science:

- **Pozyskiwanie danych** – pobranie zbioru danych z Kaggle i załadowanie go do środowiska analitycznego.
- **Czyszczenie i wstępne przetwarzanie danych** – obsługa brakujących wartości, wybór istotnych zmiennych oraz filtrowanie danych do interesującego zakresu czasowego i krajów.
- **Eksploracyjna analiza danych** – statystyki opisowe, wykresy szeregów czasowych oraz porównania między krajami.
- **Wizualizacja** – wykresy przedstawiające długoterminowe trendy i różnice w miksie energetycznym (np. wykresy liniowe, skumulowane wykresy warstwowe, wykresy słupkowe).

Wykorzystane technologie (dostosuj do swojej konfiguracji):

- Python (`pandas`, `NumPy`, `Matplotlib`, `Seaborn` / `Plotly`)
- Jupyter Notebook
- Git i GitHub