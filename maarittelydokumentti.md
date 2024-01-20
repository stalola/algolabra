# Määrittelydokumentti

- Opinto-ohjelma: Tietojenkäsittelytiede, kandidaatin tutkinto 
- Ohjelmointikieli: Python
- Kieli: Suomi 

## Aihe

Projektin tarkoituksena on kehittää Jane Austen -satunnaistekstigeneraattoria, joka hyödyntää Markovin ketjuja ja trie-tietorakennetta. Markovin ketjut mahdollistavat luonnollisen kielen kaltaisten lauseiden tuottamisen siten, että jokainen tila (sana) riippuu täysin edellisistä tiloista. Tässä projektissa on suunniteltu käytettäväksi 2-3 edellistä sanaa määrittämään seuraavan sanan todennäköisyyttä. Trie-tietorakennetta käytetään sanojen tallentamiseen ja tehokkaaseen hakemiseen. Projektin toteutus perustuu sanojen esiintymistiheyksiin ja niiden riippuvuuksiin opetusdatassa. Markovin ketjut auttavat mallintamaan näitä riippuvuuksia, kun taas trie-tietorakenne helpottaa nopeaa sanahakua ja tallentamista. Trie-rakenteella haun aikavaativuus on keskimäärin O(n).


Opetusaineistona toimivat Jane Austenin teokset, jotka ovat saatavilla [Project Gutenbergissa](https://www.gutenberg.org/cache/epub/31100/pg31100.txt). Yhteensä 8 romaania tarjoavat monipuolisen valikoiman sanoja ja lauserakenteita, joiden pohjalta generaattori tuottaa tekstiä luovasti.  Käyttäjä voi antaa ohjelmalle syötteeksi aloitussanan, jonka perusteella teksti generoidaan ja näin käyttäjä voi vaikuttaa lopputulokseen. Vaihtoehtoisesti käyttäjä voi valita, että ohjelma generoi lauseen täysin tyhjästä, mikä saattaa luoda yllätyksellisempää ja satunnaisempaa tekstiä.




## Lähteet:

[Wikipedia: Markov chain](https://en.wikipedia.org/wiki/Markov_chain)

[Wikipedia: Trie](https://en.wikipedia.org/wiki/Trie)
