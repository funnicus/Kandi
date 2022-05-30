# GraphQL ja REST: tuleeko GraphQL ottamaan REST:n paikan web-rajapintojen kuninkaana?

Jokaisen hieman monimutkaisemman verkkosivun takana on lähes poikkeuksetta sitä palveleva rajapinta, josta sivu voi hakea informaatiota näytettäväksi käyttäjilleen. Tehokkaiden rajapintojen rakentaminen ei ole kuitenkaan helppoa ja kehittäjien on aina ollut vaikea valita erilaisten arkkitehtuurimallien välillä. Representational State Transfer (REST) arkkitehtuuri web-rajapintojen toteutukseen on ollut jo pitkään monen rajapinnanrakentajan suosikki. Vuonna 2012 Facebook kehitti GraphQL:n ja uuden tavan hakea dataa web-rajapinnoista sen tarjoamalla kyselykielellä. Sittemmin GraphQL on hiljalleen saanut enemmän ja enemmän jalansijaa web-rajapintojen toteutuksissa. Jopa REST-rajapintojen kuolemaa on ennustettu, mutta muutos ei näytä tapahtuvan niin nopeasti kuin on oletettu.

Tämä tutkielma vertailee kahta tällä hetkellä suosittua tapaa luoda asiakas- palvelinsovellusten rajapintoja: GraphQL ja REST. Tämä tutkielma pyrkii etenkin selvittämään kirjallisuuskatsauksen avulla, voiko GraphQL ottaa REST:n paikan suosituimpana rajapintojen toteutustapana lähivuosina. REST:iä ja GraphQL:ää vertailevaa tutkimustyötä ei olla toistaiseksi tehty kovinkaan paljoa. Olemassa oleva tutkimustyö on keskittynyt rajapintojen kehitystyön helppouteen, turvallisuuten ja kehittäjien mielipiteisiin. Tulosten vahvistamiseksi olisi hyvä tehdä lisää tutkimustyötä tulevaisuudessa.

GraphQL:n saavuttamasta suhteellisen nopeasta suosiosta huolimatta, se ei vaikuta pystyvän syrjäyttämään REST-ekosysteemiä vielä lähivuosina. GraphQL:n tarjoama kyselykieli antaa joustavuutta, mutta tekee rajapinnoista myös hieman monimutkaisempia. On otettava myös huomioon, että REST on muodostunut muotisanaksi, millä viitataan myös REST:n kaltaisiin rajapintoihin. Näin ollen GraphQL saattaa olla jo suositumpi kuin todelliset, alkuperäisen määritelmän mukaiset REST-toteutukset.

_Tämä tutkielma on toteuttu osana Turun yliopiston tekniikan kandidaatin (tietotekniikka) tutkinto-ohjelmaa._

_Tämä repositorio sisältää tutkielman LaTex lähdekoodin._
