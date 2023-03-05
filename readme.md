W pliku loans.csv dostępne są następujące zmienne:

Debt_to_Income_Ratio – wskaźnik relacji środków przeznaczanych na obsługę zobowiązań kredytowych i innych zobowiązań finansowych do dochodu kredytobiorcy,
FICO_Score – wskaźnik oceny zdolności kredytowej obejmujący takie kwestie jak spłata zadłużenia, terminową płatność, ilość kredytów itp.
Request_Amount – kwota którą chcemy pożyczyć,
Interest – cena kredytu (różnica pomiędzy kwotą którą pożyczasz, a tą którą masz spłacić),
Approval – akceptacja (1) wniosku o pożyczkę/kredyt bądź jej brak (0).
Zmienną celu jest Approval.

Polecenia:

Ustaw jako ziarno generatora liczb losowych numerów indeksów. Podziel dane losowo na zbiory: uczący, testowy.
Zastanów się, które spośród zmiennych dostępnych w pliku będą predyktorami w tworzonym przez Ciebie modelu. Wykonaj w tym celu eksploracyjną analizę danych. Zapisz, które zmienne wybierzesz, a z których zrezygnujesz i dlaczego.
Zbuduj dwa modele klasyfikujące obserwacje ze względu na wartości zmiennej Approval: metodą k-nn oraz jedną spośród CART, C4.5/C5.0, las losowy, Extra Trees. Zwróć uwagę na konieczne założenia. Pamiętaj o doborze hiperparametrów.
Omów budowę otrzymanych modeli. Jeśli to możliwe, napisz, które predyktory modele uznały za najważniejsze.
Oceń jakość modeli obliczając współczynniki (trafność, czułość, swoistość, współczynnik f1) na zbiorach testowym i uczącym. Narysuj krzywe ROC i oblicz pola pod nimi. Czy modele działają dobrze? 