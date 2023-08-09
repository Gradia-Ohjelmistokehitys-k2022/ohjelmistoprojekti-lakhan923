## Ideointi

Omissa projekteissa yksi tärkeimmistä asioista on keksiä projekti, joka sinua itseäsi kiinnostaa. Valittu aihe määrittää työskentelysi suunnan ja vaikuttaa sekä motivaatioosi että lopputuloksen laatuun. *Voit myös hyödyntää tai jatkaa aikasemmilla kursseilla aloittamisia projekteja.* Tässä on muutamia syitä, miksi projektiaiheen valinnalla on merkittävä rooli:

1. Innostus ja motivaatio:
Valitessasi projektiaiheen, joka kiinnostaa sinua henkilökohtaisesti, on todennäköisempää, että et luovuta heti ensimmäisen haasteen edessä. 

2. Sitoutuminen ja oppiminen:
Ei varmaan ole yllättävää, että melenkiintoiseen projektiin on helpompi sitoutua ja myös oppiminen on mukavampaa.

3. Entuudestaan tuttu aihe:
Jos aihealue on sinulle entuudestaan tuttu, niin voi olla, että löydät helmommin luovia ratkaisuja ongelmiisi. Henkilökohtainen kiinnostus voi auttaa sinua sukeltamaan syvemmälle aiheeseen. Tämä tarkoittaa, että ymmärrät paremmin käyttäjän tarpeita ja pystyt luomaan heille todella hyödyllisen ratkaisun.

4. Projekti, jota jaksat kehittää myös jatkossa (esim. ohjelmisto, jolla työllistyt):
Kun työskentelet projektin parissa, joka kiinnostaa sinua, saatat löytää itsestäsi halun kehittää ja ylläpitää sitä pidemmän aikaa. Tämä voi johtaa projektin jatkokehittämiseen ja parantamiseen pitkällä aikavälillä.

Muista kuitenkin, että projektiaiheen valintaan liittyy myös huomioitavia seikkoja, kuten realistisuus, käyttäjätarpeet ja mahdolliset tekniset haasteet.  Innostus on voimakas moottori, joka auttaa sinua saavuttamaan tavoitteesi ja luomaan laadukasta ohjelmistoa.

### Esimerkkiprojekteja ja rajapintontoja:

https://www.sourcecodester.com/c-sharp

https://dev.to/samborick/100-project-ideas-oda

Voit halutessasi tutustua esim. seuraaviin apeihin:
https://developer.spotify.com/documentation/web-api/ Spotify API

https://developers.google.com/youtube/v3 Youtube web API. 

https://deckofcardsapi.com/ Deck of cards API.

https://api.adviceslip.com/ Advice API.

http://jservice.io Trivia API.

http://www.omdbapi.com/ Open movie database. 

https://spoonacular.com/ Food API.

https://funtranslations.com/api/ Fun translations API. 

https://thedogapi.com/ The dog API. 

https://developer.marvel.com Marvel api.

https://pokeapi.co/ Pokemon api. Oma pokedex? Pokemon cards jne.


## Ohjelmistosuunnittelu

Ohjelmiston saattamisesta ideasta toimivaan ohjelmaan omaa tietyt kehitysvaiheet. Yleensä järjestys on melko lailla tämä:

1. Vaatimusten määritteleminen (oikeassa projektissa asiakkaan kanssa)
2. Suunnittelu / ideointi (harjoitusprojektissa tämä on 1. vaihe)
3. Ohjelmistosuunnitelmat
4. Toteutus
5. Testaus
6. Asennus ja käyttöönotto
7. Ylläpito

Alla olevassa videossa käydään perinteiset vaiheet läpi:

[![Software Development Lifecycle in 9 minutes!](https://i.ytimg.com/vi/i-QyW8D3ei0/maxresdefault.jpg)](https://www.youtube.com/watch?v=i-QyW8D3ei0)


Modernissa kehityksessä suositaan usein ns. Agiileja menetelmiä, joissa ajatuksena on asiakkaan ja kehitystiimin jatkuva vuorovaikutus. Usein tarkoituksena on saada projektin alussa sovitut tärkeimmät toiminnot mahdollisimman nopeasti testattavaksi, jotta selviää, onko kyseinen toiminto se mitä haluttiin ja onko sitä helppo tai mukava käyttää.


Tällä kurssilla projektin pääasiallisena suunnittelualustana käytetään GitHubin projekteja (https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

Katso myös video:
[![Github project and issues](https://i.ytimg.com/vi/DuAyYsWbt5o/maxresdefault.jpg)](https://www.youtube.com/watch?v=DuAyYsWbt5o)

Alla esimerkerkki käyttötapauksista (engl. User stories) sovellukseen Lämpötilan muuntaja:

1. **Ohjelman tulee pystyä muuntamaan Fahrenheitit Celsiuksiksi.**
   - Hyväksy lämpötila-arvo Fahrenheit-yksikössä syötteenä.
   - Näytä vastaava lämpötila Celsius-asteina.

2. **Ohjelman tulee pystyä muuntamaan Celsiukset Fahrenheiteiksi.**
   - Hyväksy lämpötila-arvo Celsius-asteina syötteenä.
   - Näytä vastaava lämpötila Fahrenheit-yksikössä.

3. **Ohjelman tulee pystyä ottamaan vastaan syöte molemmissa muodoissa.**
   - Tarjoa vaihtoehto syöttää lämpötila joko Fahrenheit- tai Celsius-asteina.
   - Näytä lämpötila molemmissa yksiköissä samanaikaisesti.

4. **Ohjelman tulee selittää, miten muutos tapahtuu.**
   - Anna selitys lämpötilamuunnoksen kaavasta, jota ohjelma käyttää.
   - Näytä vaiheittainen esimerkki muunnoksesta.

5. **Ohjelman muutosten tulee olla tarkkoja.**
   - Suorita perusteelliset testit tunnetuilla lämpötila-arvoilla tarkkuuden vahvistamiseksi.
   - Käsittele mahdolliset pyöristysvirheet tai tarkkuusongelmat muunnoskaavassa.

6. **Ohjelman tulee käsitellä virheelliset syötteet, niin että ohjelma ei kaadu ja käyttäjä saa järkevän palautteen.**
   - Näytä virheviesti ja pyydä uutta syötettä, jos käyttäjä antaa ei-numeerisia tai alueen ulkopuolisia arvoja.
   - Varmista, ettei ohjelma kaadu odottamattoman syötteen takia.

7. **Ohjelmalle tulee pystyä antaa lista lämpötiloista analysointia varten.**
   - Toteuta toiminnallisuus, joka hyväksyy useita lämpötiloja ja antaa muunnetut arvot listana.


### UML-kaaviosta 

Voitte työelämässä edelleen törmätä erilaisiin kaavioihin ja kuviin. Alla on esimerkkejä erilaisita diagrammeista, joita on perinteisesti käytetty suunittelussa:

1. Käyttötapauskaavio on UML (Unified Modeling Language) -standardin osa, osa ja se kuvaa järjestelmän toimijoita, käyttötapauksia ja niiden välisiä suhteita. Vaikka yksittäiset käyttötapaukset vaikuttavat yksinkertaisilta, hyvin kirjoitetut käyttötapaukset toimivat testitapauksien pohjana. *Huom!* Vertaa yllä oleviin käyttökuvauksiin.


[![UML Use case diagram tutorial](https://i.ytimg.com/vi/zid-MVo7M-E/maxresdefault.jpg)](https://www.youtube.com/watch?v=zid-MVo7M-E)


Esimerkki laajasta käyttötapausdokumentista: https://www.kanta.fi/documents/20143/107120/Resepti+m%C3%A4%C3%A4rittely+K%C3%A4ytt%C3%B6tapaukset+apteekkitietoj%C3%A4rjestelm%C3%A4.pdf/f000a172-f0d7-25e4-c53b-ab3db332378a?t=1528014829260

2. Aktiviteettikaavio on UML (Unified Modeling Language) -standardin osa ja se kuvaa järjestelmän toimintoja ja prosesseja aikajärjestyksessä. Se on erityisen hyödyllinen kompleksisten toimintojen, prosessien ja tapahtumien havainnollistamiseen. Aktiviteettikaavio käyttää symboleja ja nuolia kuvaamaan toimintojen suhteita ja niiden välisiä siirtymiä.


[![UML Use case diagram tutorial](https://i.ytimg.com/vi/Wf_xlagfHmg/maxresdefault.jpg)](https://youtu.be/Wf_xlagfHmg)

3. Sekvenssikaavio on UML (Unified Modeling Language) -standardin graafinen kuvausväline, joka esittää järjestelmän komponenttien (kuten olioiden, metodit, MVC jne.) vuorovaikutusta ja viestien vaihtoa aikajärjestyksessä. Se havainnollistaa, miten eri toimijat ja komponentit kommunikoivat keskenään ja kuinka tieto liikkuu järjestelmässä eri vaiheissa.

[![UML Use case diagram tutorial](https://i.ytimg.com/vi/18_kVlQMavE/maxresdefault.jpg)](https://youtu.be/18_kVlQMavE)

Esimerkki Woltin Webhook-servicen toiminnasta: https://developer.wolt.com/en/docs/wolt-drive/webhooks

 
