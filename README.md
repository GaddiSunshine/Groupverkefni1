Keyrsla

Til að geta unnið sem best með þessi skjöl þarf að hafa node.js.
til að geta keyrt allar skipanir sem við notuðum þá þarf að ná í package.json skránna okkar, fara í möppuna sem verið er að vinna í í console-inu þínu og keyra eftirfarandi skipun 'npm install all'.
Þá má kíkja í package.jcon skránna og sjá þær skipanir sem við notuðum í 'scripts'.

Mest  notaða skipunin okkar var 'dev' eða 'npm run dev' sem að keyrði verkefnið í tölvunni okkar sem 'uppdate'-aðist þegar breytingar voru vistaðar í scss skránum okkar.

Mikilvægt er að vita að þegar verkefnið er keyrt lesa html skrárnar ekki styles.scss skránna heldur lesa þær styles.css skránna sem er gerð með "sass" scriptinu úr package.json skránni.

Uppsetning 

Við erum með fimm mismunandi html skrár sem eru síðurnar okkar. 
index.html er forsíðan, cart.html er karfan, course.html er námskeiðin, products.html er vörur og staff.html er starfsfólk.

styles.scss er aðal scss skráin okkar sem 'import'-ar öllum scss skrám úr scss möppunni.
í styles möppunni okkar eru níu .scss skrár, þær eru,
    config.scss
        þessi .scss skrá inniheldur allar breytur sem notaðar eru í hinum .scss skránum og er hún því "import"-uð efst í flestum hina .scss skránna.
    course.scss

    footer.scss

    forsida.scss

    fyllaUt.scss

    grid.scss

    header1.scss

    staff.scss

    vorur.scss



Hópmeðlimir

Hallur Kristinn Hallsson - hkh32@hi.is - Dæmatímahópur 2






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

