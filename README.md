SovenyvagoOllo osztály (8 pont)
Írj egy SovenyvagoOllo nev¶ osztályt, ami egy sövényvágó ollót reprezentál, egyetlen adattaggal, ami az olló élessége, ami egy 0-100 közötti lebeg®pontos szám. Minden olló legfeljebb
ilyen s¶r¶ség¶ bokrot megformázni.
Az adattagokat, valamint a metódusokat az alábbi ábrán láthatjuk. Ügyelj a megfelel®
láthatóságok használatára.
Az osztály egyetlen konstruktora az olló élességét alapból 100.0-ra állítsa.

Az elez metódus élezze meg az adott ollót. Minden élezés 15-tel javítja az olló élességét.
Ügyelj rá, hogy 100 felett nem lehet az élesség.
A vag metódus paraméterben egy bokor s¶r¶ségét kapja. A metódus térjen vissza igazzal,
ha sikerül az adott s¶r¶ség¶ bokrot megformáznia. Amennyiben az élesség miatt erre nincs
lehetőség, térjen vissza a metódus hamissal. Amennyiben sikerül a bokor megnyírása, az olló
élessége csökkenjen a formára vágott bokor s¶r¶ségével.
Bokor osztály (13 pont)
Az adattagokat, valamint a metódusokat az ábrán láthatjuk. Ügyelj a megfelel® láthatóságok
használatára.
Az osztályban deniált s¶r¶ség adattag a bokor s¶r¶ségét adja meg, 0-100 közötti lebeg®-
pontos szám, a fajta a bokor fajtája.
A forma pedig csak 0 és 4 közötti értéket vehet fel, melyek jelentése:
 0: a bokor még csak cserje
 1: a bokor egy normál, kicsi bokor
 2: formára nyírt bokor
 3: a bokor kezd elburjánzani
 4: teljesen elburjánzott formájú bokor
A Bokor osztály konstruktora állítsa be a fajtát, valamint a s¶r¶séget.
A forma metódus szövegesen visszaadja a bokor formáját, melyek az alábbiak lehetnek:
 0: "cserje"
 1: "bokor"
 2: "formara nyirt"
 3: "kisse elburjanzott"
 4: "teljesen elburjanzott"
A setForma ne csináljon semmit, ha nem megfelel® értéket próbálunk beállítani, egyébként
pedig az elvárható módon m¶ködjön.
A setSuruseg a s¶r¶séget állítja be, ha a minimumnál kisebb lenne, akkor a minimumra,
ha a maximumnál nagyobb lenne, akkor a maximumra állítja be.
A nyiras metódus egy sövényvágó ollót kap paraméterül, és az azzal kapott ollóval megpróbálja elvágni az adott s¶r¶ség¶ bokrot. Ha a vágás sikeres, állítsuk be a bokor formáját
formára nyírtra.
A novekedes metódus reprezentálja a bokor növekedését, ami annyit fog jelenteni, hogy
a formája változik: cserjéb®l bokor lesz, bokorból formás bokor, majd kissé elburjánzott bokor,
végül pedig teljesen elburjánzott bokor. Ügyelj a forma adattag lehetséges értékeire!
