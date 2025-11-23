# Notatki z uczenia maszynowego
**Uczenie maszynowe** - metody pozwalające na przybliżone wykrywanie zasad, zależności oraz wzorców występujących w zjawiskach świata rzeczywistego na podstawie obserwacji opisywanych przez cechy. Wykryte zasady pozwalają na dokonanie predykcji dla nowych danych, które nie były brane pod uwagę w procesie uczenia.

## Uczenie nadzorowane (Supervised learning)
Program dostaje przykładowe dane wejściowe i pożądane wyniki, a celem jest nauczenie się ogólnej zasady, która odwzorowuje dane wejściowe na wyniki.

### Regresja
* [Regresja liniowa](regresja-liniowa.ipynb)
    * [Zejście gradientowe]()
* [Regresja wielomianowa]()

### Klasyfikacja
* [Algorytm najbliższego sąsiada](algorytm-najblizszego-sasiada.ipynb)
* [Maszyny wektorów nośnych](maszyny-wektorow-nosnych.ipynb)
* [Drzewa decyzyjne](drzewa-decyzyjne.ipynb)
* [Klasyfikacja za pomocą sieci neuronowych](klasyfikacja-sieci-neuronowe.ipynb)

## Uczenie nienadzorowane (Unsupervised learning)
Algorytm uczący się nie otrzymuje żadnych etykiet, aby znaleźć strukturę danych wejściowych. Nienadzorowane uczenie się może być celem samym w sobie (odkrywanie ukrytych wzorców w danych) lub środkiem do osiągnięcia celu (uczenie się cech).

## Uczenie ze wzmocnieniem (Reinforcement learning)
Program komputerowy wchodzi w interakcję z dynamicznym środowiskiem, w którym musi wykonać określony cel (np. prowadzić pojazd lub grać z przeciwnikiem). Podczas poruszania się po swojej przestrzeni problemowej program otrzymuje informację zwrotną analogiczną do nagród, którą stara się zmaksymalizować.