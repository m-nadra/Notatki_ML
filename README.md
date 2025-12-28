# Notatki z uczenia maszynowego
**Uczenie maszynowe** - metody pozwalające na przybliżone wykrywanie zasad, zależności oraz wzorców występujących w zjawiskach świata rzeczywistego na podstawie obserwacji opisywanych przez cechy. Wykryte zasady pozwalają na dokonanie predykcji dla nowych danych, które nie były brane pod uwagę w procesie uczenia.

## Rodzaje uczenia maszynowego
* [Uczenie nadzorowane](#uczenie-nadzorowane-supervised-learning)
* [Uczenie nienadzorowane](#uczenie-nienadzorowane-unsupervised-learning)
* [Uczenie ze wzmocnieniem](#uczenie-ze-wzmocnieniem-reinforcement-learning)
* [Uczenie półnadzorowane](#uczenie-półnadzorowane-semi-supervised-learning)
* [Uczenie samonadzorowane](#uczenie-samonadzorowane-self-supervised-learning)

### Uczenie nadzorowane (Supervised learning)
Program dostaje przykładowe dane wejściowe i pożądane wyniki, a celem jest nauczenie się ogólnej zasady, która odwzorowuje dane wejściowe na wyniki.

#### Regresja
* [Regresja liniowa](regresja-liniowa.ipynb)
    * [Zejście gradientowe](zejscie-gradientowe.ipynb)
* [Regresja wielomianowa](regresja-wielomianowa.ipynb)

#### Klasyfikacja
* [Algorytm najbliższego sąsiada](algorytm-najblizszego-sasiada.ipynb)
* [Maszyny wektorów nośnych](maszyny-wektorow-nosnych.ipynb)
* [Drzewa decyzyjne](drzewa-decyzyjne.ipynb)
* [Regresja logistyczna](regresja-logistyczna.ipynb)

### Uczenie nienadzorowane (Unsupervised learning)
Algorytm uczący się nie otrzymuje żadnych etykiet, aby znaleźć strukturę danych wejściowych. Nienadzorowane uczenie się może być celem samym w sobie (odkrywanie ukrytych wzorców w danych) lub środkiem do osiągnięcia celu (uczenie się cech).

### Uczenie ze wzmocnieniem (Reinforcement learning)
Program komputerowy wchodzi w interakcję z dynamicznym środowiskiem, w którym musi wykonać określony cel (np. prowadzić pojazd lub grać z przeciwnikiem). Podczas poruszania się po swojej przestrzeni problemowej program otrzymuje informację zwrotną analogiczną do nagród, którą stara się zmaksymalizować.

### Uczenie półnadzorowane (Semi-supervised learning)
Rodzaj uczenia w którym część danych ma przypisane etykiety, a część ich nie posiada. Jest to połączenie uczenia nadzorowanego i nienadzorowanego.

### Uczenie samonadzorowane (Self-supervised Learning)
Etykiety generowane przez program na podstawie danych wejściowych są wykorzystywane do dalszego trenowania modelu technikami uczenia nadzorowanego.


## Uczenie głębokie (Deep learning)
**Uczenie głębokie** jest podzbiorem uczenia maszynowego, który wykorzystuje wielowarstwowe sieci neuronowe.

[**Podstawowe pojęcia związane z sieciami neuronowymi**](sieci-neuronowe-teoria.md)

### Przykłady wykorzystania uczenia głębokiego
* [Klasyfikacja za pomocą sieci neuronowych](klasyfikacja-sieci-neuronowe.ipynb)
