Kod jest próbą klasyfikowacji kotów ze zbioru cats.csv do płci żeńskiej ("F") i męskiej ("M") na podstawie dwóch zmiennych objaśniających: masy ciała (atrybut "Bwt", czyli body weight) i masy serca (atrybut "Hwt", czyli = Heart weight).
Użyte metody klasyfikacji to:
* regresja logistyczna
* maszyna wektorów nośnych (SVM)

Ponadto projekt zawiera:
* przetestowanie różnych wartości hiperparametru C (odpowiadajacego za stopień dopasowania modelu do danych)
* równoważenie wpływu liczności obiektów w każdej z klas decyzyjnych na rezultat klasyfikacji
* podział na próbę treningową i testową
* macierze pomyłek z komentarzami odnośnie do jakości klasyfikacji
