# database-SQL-project
Tietokannan suunnitteluprojekti: kuvitteellinen tietokanta vaatimusmäärittelystä SQL-kyselyihin.

- Tietokanta kuvitteelliselle aikuiskoulutusta tarjoavalle yritykselle nimeltä
Xoppi. Xopin liiketoiminta perustuu siihen, että
ulkopuolinen yritys ostaa yhdelle tai useammalle työntekijälleen
Xopin kurssin. 

- Kohteita ovat kurssi (kurssitunnus), opiskelija
(opiskelijatunnus, etunimi, sukunimi, sähköposti), maksaja
(y-tunnus, nimi, sähköposti), opettaja (henkilötunnus,
etunimi, sukunimi, sähköposti), kurssisuoritus (pvm, arvosana)

- Opiskelija suorittaa yhden tai useamman kurssin, opettaja
opettaa yhtä tai useampaa kurssia, kurssilla voi olla vain yksi
opettaja, maksaja maksaa yhden tai useamman kurssisuorituksen,
kurssisuoritukseen liittyy olennaisesti myös maksajan y-tunnus ja
opiskelijan opiskelijatunnus.

Xopin opiskelijatietokantaa käyttävät vain Xopin työntekijät,
eikä siltä vaadita kovin korkeaa suorituskykyä, verrattuna
esimerkiksi verkkokauppoihin. Toisaalta tietokantaan
tallennetaan henkilötunnuksineen sellaista tietoa, joka
vaatii luotettavaa tietoturvaa. 

Ehkä tällaisen yrityksen
alkutaipaleella, kun toiminta on vasta alussa, ja asiakkaita sekä
opiskelijoita on vähän, tietokannan tallentaminen sovellukseen
voi olla riittävä tallennusmuoto. Jos yrityksessä on
resursseja ja/tai osaamista, keskitetty palvelin olisi varmasti
tietoturvan kannalta parempi vaihtoehto alusta saakka. Jos
liiketoiminta-analyysien perusteella tulevaisuuden näkymät ovat
hyvät, tietokanta myös kasvaa nopeasti. Etenkin, kun Xoppi
tarjoaa vain verkkokursseja, ne skaalautuvat suuremmille
opiskelijajoukoille paremmin, kuin fyysiseen paikkaan sidotut
kurssit. Jos liiketoiminta lähtee kasvuun, ja kurssit
skaalautuvat suurille opiskelijajoukoille, viimeistään sitten voi
olla tarpeen harkita keskitetyn tietokantapalvelimen käyttöä.

Yrityksellä on vain yksi toimipiste
ja kaikki opetus tapahtuu toimipisteen studiossa, joten näin
ollen hajauttamiselle ei ainakaan toimintaviiveen
kannalta ole tarvetta. Tietokanta ei myöskään vaadi suurta
toimintakykyä tai -varmuutta. Tietokantaan ei tallenneta
sellaista kriittistä tietoa, joka ongelmatilanteissakin tulisi
olla joka hetki saatavilla.

Minulla ei ole koulutusta saati kokemusta
liiketoiminnallisiin tekijöihin liittyen,
mutta uskoisin, että liiketoiminnassa on
tärkeää tallentaa ja analysoida
rahaliikenteeseen liittyvää tietoa. Näin
ollen uskon, että myös opiskelijatietokannan dataa on hyödyllistä
tallentaa tietovarastoon. Yrityksellä voisi olla tarve
analysoida esimerkiksi liiketoiminnan kehitystä pitkällä
aikavälillä opiskelijoiden ja kurssisuoritusten määrien avulla
tai seurata asiakkuuksien pysyvyyttä tai tilausfrekvenssiä
pitkällä aikavälillä. Jälkimmäistä voi toki olla mahdollista
seurata ja analysoida myös liiketoimintaan liittyvän muun
tietokannan datan perusteella. Opiskelijatietokannan avulla se
onnistuisi listaamalla ja käsittelemällä halutulla tavalla
kurssisuoritusten päivämääriä maksajien y-tunnuksen mukaan.

Uskoisin, että relaatiotietokanta on sopiva paradigma
opiskelijatietokannan ylläpitoon muun muassa siksi, että
tietokannalta ei vaadita suurta joustavuutta ja sen sisältämä
data sopii hyvin taulukkomuotoon. Ehkä liiketoiminnan
rahaliikenteeseen liittyvän tiedon tallentamisessa ja
käsittelyssä voi olla enemmän tarvetta joustavuudelle ja
kaavioille, mutta liiketoimintatarpeet ovat osaamiseni
ulkopuolella, joten en ota siihen kantaa. Liiketoimintaan
liittyvien tietokantojen lisäksi kyseisellä yrityksellä on
varmasti tarve tallentaa myös muuta, kuten henkilöstön tietoja.
Tässä lopputyössä on keskitytty vain opiskelijatietokannan
luomiseen.

