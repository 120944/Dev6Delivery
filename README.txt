*****************
*TESTS TOEVOEGEN*
*****************
Om tests toe te voegen volg je de volgende stappen:
- Maak een bestand in   test_classes als je een unittest maakt van een class /
                        test_functions als je een unittest maakt van een functie
 genaamd test_<CLASSNAAM>

- Schrijf hierin je unittest, noem de class Test<CLASSNAAM> en de methodes/functies test_<FUNCTIENAAM>
+ Je kunt in een test class een setup en teardown functie toevoegen, deze wordt voor -elke- opnieuw uitgevoerd,
    de setup voor, en de teardown na.

De nose framework zal hierna alle goed genaamde bestanden en tests uitvoeren wanneer je runner.py uitvoert.


********************
*OVERIGE INFORMATIE*
********************
De Counter en test_Counter bestanden zijn voorbeelden van unittesting en dus niet bedoeld voor meelevering
in het eindproduct.

