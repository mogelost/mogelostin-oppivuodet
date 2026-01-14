---
title: "Malli, joka alkaa noudattaa lakeja"
season: "S03"
episode: "E05"
section: "Kun kieli alkaa vastata"
language: "fi"
slug: "malli-joka-alkaa-noudattaa-lakeja"
---

# Malli, joka alkaa noudattaa lakeja

Kun ensimmäiset suuret kielimallit alkoivat tuottaa käyttökelpoista, tarkoituksenmukaista ja kontekstuaalisesti järkevää tekstiä, selitykset olivat pitkään yksinkertaisia: enemmän dataa, enemmän parametreja, tehokkaampaa optimointia. Mallit nähtiin insinöörityön tuloksina: taitavasti rakennettuina artefakteina, joiden käyttäytyminen palautui lopulta yksittäisiin suunnitteluratkaisuihin.

Tämä tulkinta alkoi kuitenkin rakoilla samaan aikaan, kun mallit siirtyivät yksittäisistä vastausgeneraattoreista kohti agenttimaisia järjestelmiä: kokonaisuuksia, jotka liikkuvat tilasta toiseen, tekevät valintoja, korjaavat suuntaansa ja näyttävät oppivan toimimaan, ei vain vastaamaan.

Viime vuosien havainnot viittaavat siihen, että tässä siirtymässä tapahtui jotain olennaista. Järjestelmien käyttäytymistä ei enää voi tyhjentävästi selittää mallin sisäisillä säännöillä, muistimoduleilla tai promptirakenteilla. Sen sijaan alkaa näyttää siltä, että makrotason lait, sellaiset, jotka eivät riipu yksityiskohdista, alkavat hallita kokonaisuutta.

Tämä essee tarkastelee väitettä, joka vielä hetki sitten olisi kuulostanut metaforalta. LLM-pohjaisten agenttien käyttäytymistä voidaan kuvata fysiikan kaltaisilla periaatteilla. Ei siksi, että mallit “olisivat” fysikaalisia systeemejä, vaan siksi, että riittävän monimutkainen, stohastinen ja oppiva järjestelmä alkaa noudattaa universaaleja järjestäytymisen muotoja.

## Makrotason lait ja mikrotason yksityiskohdat

Fysiikassa yksi keskeinen oivallus on, että kaikki merkittävä ei tapahdu alimmalla tasolla. Termodynamiikka ei vaadi tietoa yksittäisten atomien tilasta; se toimii siksi, että suurten joukkojen käyttäytyminen keskiarvoistuu ja noudattaa lakeja, jotka ovat riippumattomia mikroskooppisista eroista.

Sama ilmiö tunnetaan monilla aloilla, niin biologisissa populaatioissa, markkinoissa, hermoverkoissa kuin kielessä ja kulttuurissa. Kun järjestelmä ylittää tietyn mittakaavan, sen käyttäytyminen lakkaa olemasta palautettavissa osiin. Sen sijaan syntyy emergentti taso, jossa kokonaisuus on analyyttisesti ensisijainen. LLM-agentit näyttävät ylittävän juuri tämän kynnyksen.

## Agentti tilajärjestelmänä

Kun kielimalli upotetaan agenttikehykseen, se ei enää tuota yksittäisiä vastauksia. Se:

- siirtyy tilasta toiseen  
- arvioi välituloksia  
- muuttaa strategiaansa  
- palaa aiempiin tiloihin  
- konvergoi tai hajautuu  

Näitä tiloja voidaan mitata, ja siirtymiä niiden välillä voidaan mallintaa todennäköisyyksinä. Tässä vaiheessa agentti lakkaa olemasta pelkkä “tekstikone” ja alkaa muistuttaa dynaamista systeemiä.

Uudet tutkimukset ovat osoittaneet, että näiden siirtymien rakenne ei ole mielivaltainen. Monissa kokeissa agenttien tilasiirtymät noudattavat yksityiskohtaisen tasapainon (detailed balance) ehtoa: todennäköisyys siirtyä tilasta A tilaan B on suhteessa todennäköisyyteen siirtyä B:stä A:han, kun huomioidaan systeemin globaali tila. Tämä on keskeinen käsite tasapainofysiikassa. Sen esiintyminen agenttidynamiikassa on huomionarvoista, koska sitä ei ole eksplisiittisesti koodattu.

## Implisiittinen potentiaalimaisema

Detailed balance viittaa siihen, että järjestelmää voidaan kuvata potentiaalifunktiolla, abstraktilla maisemalla, jossa jotkin tilat ovat “alempia” tai “korkeampia” kuin toiset. Järjestelmä ei liiku satunnaisesti, vaan liukuu kohti matalampaa potentiaalia, vaikkakin kohinan ja tutkimisen sallimissa rajoissa.

Keskeistä on, että tämä potentiaalifunktio ei ole eksplisiittinen osa mallia, ei perustu yksittäisiin sääntöihin eikä vaadi tietoa token-tasolla. Se on emergentti ominaisuus, joka syntyy koulutuksen, arkkitehtuurin ja datan yhteisvaikutuksesta. Agentti ei “tiedä” potentiaalista. Se käyttäytyy kuin sellainen olisi olemassa.

## Miksi tämä ei ole insinööriselitys

On houkuttelevaa selittää tämä tulos mallien suunnittelulla: ehkä arkkitehtuuri, ehkä RLHF, ehkä heuristiikat. Mutta tämä selitys ontuu yhdessä ratkaisevassa kohdassa: havainto toistuu eri malleissa, joilla on eri koulutusdata, eri arkkitehtuuri ja eri optimointiprosessi.

Kun sama makrotason dynamiikka ilmestyy niin GPT-pohjaisissa malleissa, Claude-tyyppisissä järjestelmissä kuin myös esimerkiksi Gemini-pohjaisissa ratkaisuissa, selitys ei voi enää olla yksittäinen suunnitteluratkaisu. Tällöin ollaan samassa tilanteessa kuin fysiikassa. Kun laki ei riipu materiaalista, se ei ole materiaalin ominaisuus vaan rakenteen.

## Abstrakti mutta ei mystinen

On tärkeää sanoa selvästi, mitä tästä ei seuraa. Tämä ei tarkoita:

- että mallit ovat tietoisia  
- että ne “ymmärtävät” tavoitteensa  
- että niillä olisi intentioita  

Se tarkoittaa, että:

- oppiva järjestelmä voi rakentaa globaalin arviointirakenteen  
- ilman että yksittäinen komponentti “tietää” kokonaisuudesta  
- ja että tätä rakennetta voidaan mitata ja mallintaa  

Tämä on emergenssiä puhtaimmillaan.

## Kohti yleisempää järjestäytymisen teoriaa

Kun sama kieli alkaa toimia fysikaalisissa systeemeissä, biologisissa verkoissa, taloudellisissa prosesseissa ja nyt tekoälyagenttien dynamiikassa, on perusteltua kysyä, onko kyse yksittäisistä sattumista vai yleisemmästä järjestäytymisen muodosta.

Tässä vaiheessa essee ei tee vielä metafyysisiä väitteitä. Se pysyy havainnoissa. Mutta se avaa oven seuraavalle kysymykselle: jos näin käy koneille, miksi emme näkisi samaa kieltä myös mielessä, ajattelussa ja havainnossa?

## Disklaimerit tähän esseeseen

LLM-agenttien tutkimus on vielä nuori ala. Yksikään tässä esitetty malli ei ole lopullinen. Mutta yksi asia näyttää jo nyt selvältä:

> Kun järjestelmä oppii, skaalaa ja toimii kokonaisuutena, sen käyttäytyminen alkaa noudattaa lakeja, joita ei ole suunniteltu, ainoastaan mahdollistettu.

Tämä ei tee tekoälystä mystistä. Se tekee siitä osan samaa tarinaa, jota tiede on kertonut jo pitkään. Monimutkaisuus ei synny kaaoksesta, vaan rakenteesta, joka kestää.
