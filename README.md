# DesignLaboratoryEiT
16.10.2022
W pierwszym tygodniu pracy nad projektem, zapoznaliśmy się z środowiskiem programistycznym oraz nowym dla nas CircuitPythonem.
Posiłkowaliśmy się poniższym filmem w serwisie YouTube
https://www.youtube.com/watch?v=opes_7Uf49U
Korzystaliśmy również z artykułu na stronie AdaFruit, w którym mogliśmy zapoznać się z aspektami fizycznymi oraz programistycznymi platformy Clue.
https://learn.adafruit.com/adafruit-clue/circuitpython
24.10.2022
W drugim tygodniu pracy nad projektem, znaleźliśmy przykładowe kody programowania smartwatcha. W środowisku CircuitPython zaprogramowaliśmy nasze urządzenie i próbowaliśmy przeanalizować znalezione kody programów.
Przykładowe programy jakie testowaliśmy:
Kompas: https://github.com/davedice/Adafruit-CLUE-Compass
Termometr: https://learn.adafruit.com/adafruit-clue/clue-temperature-and-humidity-monitor
CLUE Spirit Level: https://learn.adafruit.com/adafruit-clue/clue-spirit-level
CLUE Height Calculator: https://learn.adafruit.com/adafruit-clue/clue-height-calculator

30.10.2022 (tydzień 3)
Pomocna okazała się być strona circuitpython.org, gdzie pod adresem https://docs.circuitpython.org/projects/clue/en/latest/api.html znaleźliśmy przykłady obsługi czujników, przycisków, touchpadów itd. Podczas pracy z biblioteką clue zauważyliśmy, że rezerwuje ona niektóre porty na własny użytek i korzystając z niej, nie można korzystać np. z biblioteki digitalio. Napisaiśmy kilka prostych programów w których możliwe jest sterowanie diodą LED oraz RGB za pomocą przycisków, touchpadów czy za pomocą gestów.
