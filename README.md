# C-Alkeet-Viikko-4
Viikko 4, tehtävät 1-8 (Funktiot ja aliohjelmat, README kansiossa laajemmin tehtävistä

1. Tee ohjelma, jossa on pääohjelma (main-funktio) ja aliohjelma (funktio) nimeltä tulosta().
Pääohjelmasta kutsutaan em. aliohjelmaa, joka tulostaa näytölle ”Hei maailma!”.

2. Tee ohjelma, jossa on pääohjelma (main-funktio) ja aliohjelma (funktio) nimeltä lue().
Pääohjelmasta kutsutaan em. aliohjelmaa, joka tulostaa näytölle ”Anna kokonaisluku”.
Tässä aliohjelmassa luetaan myös kokonaisluku ja palautetaan se pääohjelmaan, joka
tulostaa luvun näytölle.

3. Muuta edellistä ohjelmaa siten, että lisäät siihen luvunTulostus() nimisen aliohjelman. Tätä
aliohjelmaa kutsutaan pääohjelmasta (sitten, kun luku on luettu) ja siihen välitetään luettu
kokonaisluku. luvunTulostus() aliohjelma tulostaa siihen välitetyn luvun näytölle.

4. Tee ohjelma jossa on pääohjelma (main-funktio) sekä yksi funktio eli aliohjelma, joka kysyy
float-luvun käyttäjältä, kertoo luvun kolmella ja palauttaa tuloksen main()-funktiolle, jossa
tulos tulostetaan näytölle.

5. Tee ohjelma, jossa on funktio vertaile() johon viedään kaksi kokonaislukua. Tämä funktio
vertailee niiden suuruutta ja tulostaa ne suuruusjärjestyksessä näytölle (suurin ensin).

7. Tee ohjelma, jossa välität funktioon merkkijonon (merkkitaulukon), joka on määritelty
paikalliseksi (ei globaali) muuttujaksi. Funktiossa tämä merkkijono tulostetaan näytölle.

8. Tee ohjelma, joka lukee käyttäjän syöttämän kokonaisluvun (int) ja desimaaliluvun (double)
char-taulukkoon. Sitten ohjelma summaa luvut ja tulostaa näyttöön. (Käytä <stdlib.h>
kirjaston atoi()- ja atof()-funktioita, jotka muuttavat merkkijonon luvuksi
int luku=atoi(merkkijono); //muuntaa merkkijonon kokonaisluvuksi
double luku2=atof(merkkijono); //muuntaa merkkijonon double luvuksi)
