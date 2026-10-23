# Tähtisumu

Tähtisumu on Godotilla toteutettu ylhäältä kuvattu avaruusräiskintäpeli. Ohjaa
avaruusalusta, tuhoa aalto kerrallaan aluksia ja selviydy mahdollisimman pitkään
kasvavan vaikeustason keskellä.

## Pelin idea

Pelaaja puolustautuu avaruudessa lähestyviä vihollisia vastaan. Viholliset
ilmestyvät pelikentän reunoilta ja hakeutuvat pelaajan luo. Aalto päättyy, kun
kaikki sen viholliset on tuhottu, minkä jälkeen seuraava aalto alkaa suuremmalla
vihollismäärällä.

Peli päättyy, kun aluksen kaikki elämät ovat loppuneet. Tavoitteena on saavuttaa
mahdollisimman monta aaltoa.

## Keskeiset ominaisuudet

- Aaltoihin perustuva selviytymispeli, jossa vaikeustaso kasvaa etenemisen
  myötä.
- Hiirellä suunnattava avaruusalus ja ammuttavat projektiilit.
- Kaksi vihollistyyppiä:
  - tavallinen vihollinen, joka syöksyy kohti pelaajaa
  - kestävämpi vihollinen, joka vaatii useita osumia
- Dash-liike, joka antaa hetkeksi suuren nopeuden ja aktivoi suojakilven.
  Suojakilven avulla vihollisia voi tuhota törmäämällä dashin aikana.
- Portaalit, joiden avulla pelikentällä voi siirtyä nopeasti paikasta toiseen.
- Vihollisista saatavat esineet:
  - **Health** lisää yhden elämän
  - **Rapid Fire** nopeuttaa ampumista hetkellisesti
- Pelin aikainen HUD näyttää elämät, nykyisen aallon, aallon vihollismäärän
  ja dashin latautumisen.
- Tauotus, uudelleenaloitus ja paluu päävalikkoon.
- Pixel art -grafiikka, animaatiot, äänitehosteet ja taustamusiikki.

## Ohjaus

| Toiminto | Näppäin |
| --- | --- |
| Liiku eteenpäin hiiren suuntaan | `W` + hiiri |
| Liiku taaksepäin hiirestä poispäin | `S` + hiiri |
| Liiku vasemmalle | `A` |
| Liiku oikealle | `D` |
| Ammu | hiiren vasen painike |
| Dash ja suojakilpi | `Shift` |
| Tauko | `Esc` |

Alus kääntyy hiiren osoittamaan suuntaan. Dashilla on latausaika, joten sitä
ei voi käyttää jatkuvasti.

## Pelaaminen

1. Valitse päävalikosta **New Game**.
2. Liiku ja tähtää hiirellä.
3. Ammu lähestyviä vihollisia ennen kuin ne osuvat alukseen.
4. Käytä dashia sekä väistämiseen että vihollisten tuhoamiseen.
5. Kerää vihollisten pudottamat esineet.
6. Selvitä aallot ja yritä rikkoa oma ennätyksesi.

## Käynnistäminen

### Valmis Windows-versio

Jos käytössäsi on valmis Windows-julkaisu, käynnistä sen mukana toimitettu
Windows-suoritettava tiedosto, esimerkiksi `Tähtisumu.exe`.

### Godot-editorissa

1. Asenna [Godot 4.3](https://godotengine.org/download/).
2. Avaa tässä hakemistossa oleva `project.godot` Godot-editorissa.
3. Käynnistä projekti painamalla **Play**. Päävalikko avautuu automaattisesti.

## Teknologia

- [Godot Engine](https://godotengine.org/)
- Godot 4.3
- GDScript
- 2D-peli ja yhteensopivuusrenderöijä

## Lisenssi

Projekti on julkaistu MIT-lisenssillä. Lisätiedot löytyvät tiedostosta
[`LICENSE`](LICENSE).
