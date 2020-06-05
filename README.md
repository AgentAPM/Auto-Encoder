# Auto-Encoder

W archiwum znajdują się dwa rozwiązania: sieć neuronowa i generator. Mają one ustawione względne ścieżki, więc wystarczy, że ich katalogi będą się znajdowały w jednym folderze.
Sieci można używać od razu do wczytania synaps z pliku i testowania danych, ale z racji oszczędności miejsca zbiór próbek treningowych jest pusty.
Można go wypełnić generatorem, podając w konsoli wymiary próbki oraz ich liczbę (sieć przyjmuje obrazy o wymiarach 24x24, a przykładowe zapisy były trenowane na zbiorze 5000 próbek).
Wybranie opcji testowania zbada pliki w folderze Samples zaczynające się od "test". W wyniku podany będzie loss, oraz dokładność liczona na zasadzie: część pikseli zaklasyfikowanych prawidłowo: jasne jako jasne, ciemne jako ciemne. Również, w folderze Display zostaną utworzone zestawienia jak powinien wyglądać wynik, z tym, co sieć faktycznie zwróciła.
