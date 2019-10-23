Keyrsla

Til að geta unnið sem best með þessi skjöl þarf að hafa node.js.
til að geta keyrt allar skipanir sem við notuðum þá þarf að ná í package.json skránna okkar, fara í möppuna sem verið er að vinna í í consoleöinu þínu og keyra eftirfarandi skipun 'npm install all'.
Þá má kíkja í package.jcon skránna og sjá þær skipanir sem við notuðum í 'scripts'.

Mest  notaða skipunin okkar var 'dev' eða 'npm run dev' sem að keyrði verkefnið í tölvunni okkar sem 'uppdate'-aðist þegar breytingar voru vistaðar í scss skránum okkar.

Uppsetning 

Við erum með fimm mismunandi html skrár sem eru síðurnar okkar.



## Lýsing á verkefni

`README.md` skrá skal vera í rót verkefnis og innihalda:

* Upplýsingar um hvernig keyra skuli verkefnið
* Lýsingu á uppsetningu verkefnis, hvernig því er skipt í möppur, hvernig CSS er skipulagt og fleira sem á við
* Upplýsingar um alla sem unnu verkefnið
* Leyfilegt er að halda eftir þessari verkefnalýsingu en hún skal þá koma _á eftir_ ykkar lýsingu

## Tæki og tól

Setja skal upp Sass og stylelint fyrir verkefnið. Gefin er `styles.scss` skrá með grunn upplýsingum.

Gefin er `.stylelintrc` skrá sem segir til um hvernig lint fyrir `scss` skrár skuli háttað.

Í `.gitignore` er `styles.css` hunsað sem þýðir að það verður _ekki_ checkað inn. Það er gert vegna þess að það er búið til af sass út frá `styles.scss`

