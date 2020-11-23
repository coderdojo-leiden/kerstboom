# Hang ballen aan de kerstboom

Wat is een kerstboom zonder ballen? We gaan ballen aan de kerstboom toevoegen door gebruik te maken van het `sphere` (bol) blok uit de 3D Objects groep. Sleep deze naar het werkveld en stel de radius (straal) in op 1.5

![sphere](images/sphere.png)

Druk op **Render**.\
Je ziet nog geen bal verschijnen, omdat de straal van de bal kleiner is dan de dikte van de kerstboom. Gebruik een `translate` blok om de bal een betere plek in de kerstboom te geven. Stel X in op -8, Y op 5 en Z op 2.

![translate](images/translate4.png)

Druk op **Render**.

![translate-resultaat](images/translate4-resultaat.png)

Laten we meteen een tweede bal toevoegen aan de rechterkant van de kerstboom. Kopieer de blokken van de eerst bal en verander in het `translate` blok van de kopie de X in 8.

![twee-ballen](images/twee-ballen.png)

Druk op **Render**.

![twee-ballen-resultaat](images/twee-ballen-resultaat.png)

Omdat we meer ballen aan de kerstboom willen hangen die in paren voorkomen, gaan de we twee ballen die we nu hebben bij elkaar zetten met een `union` blok.

![union](images/union3.png)

Kopieer het `union` blok met de twee ballen en verander in de kopie de X in -5 (eerste bal) respectievelijk 5 (tweede bal) en de Y in 17 (beide ballen).\
Kopieer het `union` blok met de twee ballen nog een keer en verander in de kopie de X nu in -3 en 3 en de Y in 27.\
Gebruik nog een `color` blok om de drie paar ballen een mooie kleur te geven.

![drie-paar-ballen](images/drie-paar-ballen.png)

Druk op **Render**.

![drie-paar-ballen-resultaat](images/drie-paar-ballen-resultaat.png)

Voeg als laatste het `color` blok met alle ballen toe aan het `union` blok van je kerstboom.\
En vergeet niet je project op te slaan!

[De volgende stap >>](stap_6.md)

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons-Licentie" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />Dit werk valt onder een <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/deed.nl">Creative Commons Naamsvermelding-NietCommercieel-GelijkDelen 4.0 Internationaal-licentie</a>.
