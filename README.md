# Analiza cen kukurydzy w R
Projekt przedstawia analizę szeregów czasowych na przykładzie notowań cen kukurydzy. Celem jest zbadanie, jak dobrze różne modele wielomianowe opisują zmienność cen w czasie oraz wybór najlepszego dopasowania przy użyciu kryterium informacyjnego AIC.

# Przebieg analizy
Dopasowano modele o rosnącym stopniu złożoności:
- Model liniowy (stopień 1)
- Model kwadratowy (stopień 2)
- Model sześcienny (stopień 3)

Dla każdego modelu wykonano:
- estymację parametrów
- wizualizację dopasowania
- analizę reszt
- obliczenie wartości AIC.
- 
Przy pomocy zaimplementowanej funkcji przetestowano modele stopnia od 1 do 25 oraz porównano ich jakość za pomocą kryterium AIC.Wykonano wizualizację zależności: stopień wielomianu vs AIC.

# Wnioski 
- zwiększanie stopnia wielomianu poprawia dopasowanie tylko do pewnego momentu
- zbyt złożone modele prowadzą do przeuczenia
- kryterium AIC jest skutecznym narzędziem wyboru modelu
