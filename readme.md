# Narzędzia pomocnicze
Podczas implementacji użyliśmy biblioteki o nazwie OpenCV, wspiera ona wiele algorytmów zwiazanych z rozpozanwaniem obrazów oraz uczeniem maszynowym

# Dane wejściowe
W implementacji ustawione zostały między innymi, maksymalny próg na 100, nazwy okienka czy też ratio które jest mnożnikiem używanym przy obliczeniu drugiego progu podczas wykonywania alogrytmu. Mnożnik ten otrzymał wartość 3 jako iż jest to zalecana wartość przez twórców biblioteki OpenCV

max_Threshold = 100
window_name = 'Canny'
title_trackbar = 'Min Threshold:'
ratio = 3 
apertureSize = 3 
pathToImage = "ścieżka_do_pliku_z_obrazem"

# Działanie
Wykonanie wykrycia krawędzi zachodzi poprzez użycie metody z biblioteki CV2 zaimportowanej pod nazwą cv jako cv.Canny(). Metoda ta jako argumenty przyjmuje wcześnie przeprocesowany obrazek, pierwszy próg używany w procedurze, drugi próg oraz operator Sobela, ktory jest uzywany do wykrywania krawedzi w cyfrowym przetwarzaniu obrazow

# Przykłady
### 1. Postać z tłem o jasnym kolorze
[![N|Solid](https://i.imgur.com/ZWeh34l.png)](https://i.imgur.com/ZWeh34l.png)
### 2. Postać bez tła
[![N|Solid](https://i.imgur.com/iRKx0hr.png)](https://i.imgur.com/iRKx0hr.png)
### 3. Postać z różnokolorowym tłem
[![N|Solid](https://i.imgur.com/vkTbBnD.jpg)](https://i.imgur.com/vkTbBnD.jpg)
[![N|Solid](https://i.imgur.com/xKwtXMl.png)](https://i.imgur.com/xKwtXMl.png)