[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/6kTgNeEK)
# Maze race
Cílem tohoto projektu bylo vytvoření herního prostředí a assetů pro hru **Maze race**.
## Děj hry
Hra se odehrává v bludišti. Hráč má za úkol se dostat co nejrychleji z jednoho konce bludiště na druhý. Maximální limit pro protnutí bludiště je **180 sekund**. Po cestě se ovšem naráží na různé přeměty a překážky, je dobré se některým vyvarovat, protože totiž ubírají drahocenný čas.
## Mechanika hry
Čas se začně odpočítávat po hráčově prvním pohybu. Čas hráč stále vidí, aby měl představu o průběhu hry. Pokud hráč v některém místě narazí na nějaký z předmětů musí ho sebrat, respektive pokud na něj narazí, předmět ho nějaký způsobem ovlivní (viz. předměty). Předměty jsou distribuovány po scéně zcela náhodně.
### Výpočet skóre
Po objevení konce bludiště se hráčovi stopne čas, a sečtou body. Výsledný čas v sekundách (i s penalizacemi) se odečte od 180 a přičtou se všechny posbírané body.
#### Příklad
Hráč zdolal celé bludiště za 87 sekund, cestou dostal penalizaci 8 sekund a posbíral 30 bodů. Jeho výsledné skóre je 180-87-8+30= 115.





## Jednotlivé Assety
Assety jsou modelované v Blenderu a texturované v Substance Painteru. Při importovaní do Unikty je důležité myslet na to, že některé assety nemají správnou velikost, takže je potřeba si trošičku pohrát s velikostí.
### Labyrint
![Labyrit](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/Maze.PNG)


### Postavy
Hráč má na výběr z několika postav.
#### Griffin the Guide
![Griffin the Guide](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/ch.1.PNG)
Je ze všech nejrychlejší, ale nemá dostatek síly, aby přemístil překážky kategorie větší než 1.
#### Salem the Seeker
![Salem the Seeke](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/ch.2.PNG)
Má sílu odstranit i ty nejtežší překážky. Pokaždé, když odstraní z cesty sud, dostane navíc 3 sekundy.
#### Quinn the Quester
![Quinn the Quester](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/ch.3.PNG)
Pokud narazí na láhev, nemusí se vracet na start.

### Překážky
V bludišti se nachází překážky. Jsou rozděleny do 3 kategorii podle obtížnosti. Většinou jdou odtlačit, nicméně těm největším se může postavit jen postava **Salem the Seeker**. 
#### Paleta
Překážka kategorie 1. 
![Paleta](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/Paleta.PNG)
#### Box
Překážka kategorie 2.
![Box](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/Box.PNG)
#### Sud
Překážka kategorie 3. Dokáže ji odstarnit je **Salem the Seeker**
![Sud](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/Barrel.PNG)
#### Knihovna
Překážka kategorie 2.
![Shelf](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/Shelf.PNG)

### Předměty
Krom toho, že hráč se musí dostat z bludiště za co nejkratší čas, tak cestou naráží na různé předměty, které mu můžou bud pomoci nebo naopak znesnadnit průběh hry.

#### Zkumavka
Hráč za ní dostane nejvíce bodů (30b) a uberemu 2 sekundy. Ovšem je nejvzácnější, takže v celé hře jsou vždycky jen tři.
![Zkumavka](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/Zkumavka.PNG)
####  Zelený krystal
Krystal dá hráčovi 5 bodů.
![Zelený krystal](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/zelen%C3%BD%20krystal.PNG)
####  Červený krystal
Červený krystal přidá hráčovi 2 sekundy navíc.
![Červený krystal](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/%C4%8Derven%C3%BD%20krystal.PNG)
#### Láhev
Pokud hráč narazí na láhev, musí se vrátí se zpátky na start.
![Láhev](https://github.com/pslib-cz/2022l4web-app-mockup-BinBaldin/blob/main/lahev.PNG)



