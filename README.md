# historyOfFootball

Celem projektu jest analiza danych o meczach piłkarskich drużyn narodowych od 1872 roku. 
Analiza jest podstawą do wyciągnięcia wniosków i lepszego zrozumienia ewolucji piłki nożnej na świecie.

Pierwszym krokiem był przegląd dostępnych danych i zaprojektowanie struktury danych z podziałem na tabele facts i dimensions.

Następnie założony został serwer SQL na platformie Azure oraz database, w którym utworzona została struktura tabel zgodna z wcześniej zdefiniowanym schematem.


Kolejnym etapem był proces ETL, który podzielony został na dwa kroki:
1. Czyszczenie i obróbka danych .csv i eksport gotowych tabel dim i facts do plików .csv
2. Załadowanie plików do bazy danych za pomocą SSIS

Na koniec nastąpiła integracja PowerBI z serwerem i przygotowany został dashboard pokazujący ewolucję footballu międzynarodowego na przestrzeni dekad. 
