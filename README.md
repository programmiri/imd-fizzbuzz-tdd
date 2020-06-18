# FizzBuzz in TDD

## Installation

`yarn install` oder `npm install`.

## Scripts

- `yarn watch` öffnet den Testrunner im "Watch" Modus. Die Test werden jedesmal wieder ausgführt, wenn du eine Code/Test Datei speicherst.
- `yarn test` lässt die Tests einmal durchlaufen

## Aufgabe

-  Schreibt ein Programm, dass die __Zahlen 1 bis 100__ ausgibt.
-  Wenn eine Zahl glatt __durch 3 teilbar__ ist, soll statt der Zahl das Wort __"Fizz"__ ausgegebenwerden.
-  Wenn eine Zahl glatt __durch 5 teilbar__ ist, soll statt der Zahl das Wort __"Buzz"__ ausgegebenwerden.
-  Wenn eine Zahl glatt __durch 3 und 5 teilbar__ ist, soll statt der Zahl das Wort __"FizzBuzz"__ ausgegeben werden.


__Und das ganze natürlich test-driven!__


## Ressourcen

Das Testing Tool, dass ihr benutzt, ist [Jest](https://jestjs.io/docs/en/getting-started). In der Doku findet ihr alles was ihr braucht.

## Tips

Die Beschreibung der Tests kann auf verschieden Arten geschrieben werden. Ich bevorzuge, in dem `it` Part eine Anforderung zu formulieren wie "it `"returns '0' for number 0"`". Formulierungen wie `"should return '0' for number 0"` sind ebenfalls oft genutzt. Macht das, wie ihr mögt - wichtig ist, dass ihr versucht, in den Beschreibungne mehr Information über den Code zu geben. Dann haben eure Tests auch Nutzen als Dokumentation. 

Viel Spaß 😄
