# MEESKOND: Tooteanalüüsi osakond |  NÄDAL: 1  |  TEGELANE: Toomas Kask

## ANDMEMAASTIK (Data Landscape):

- **sales** (tehingud): 15234 rida, 11 veergu

peamine leid : kuupäevad on segaformaadis, store_location puudub 5204 real (34%). 1487 real puudub customer_id. See tähendab, et ligi 10% müükidest ei ole seostatavad püsiklientidega
Tallinna vaade: Viimase 15 tehingu detailne kontroll paljastas süsteemseid duplikaate ja tühje väärtusi.
Müügisummade vahemik on ebatavaliselt suur: suurim tehing oli summas 2 170.40 €, kuid tuvastasin ka vigaseid andmeid, kus väikseim väärtus oli -1 405.32 €.
Negatiivsed summad vajavad täiendavat kontrolli - võivad tähendada tagastusi.
Kaupluste koormus:
1. Tallinn: 5 704 tehingut
2. Tartu: 2 708 tehingut
3. Pärnu: 1 618 tehingut

- **customers**: 3150 rida, 9 veergu

Peamine leid: Enamik andmetest on täidetud, kuid puuduvad väärtused esinevad peamiselt veergudes email (380 puudu ehk 12,1% kliendibaasist; 510 dubleeritud ehk 16,2%) ning loyalty_tier (1260 puudu ehk 40%).
Linnade (city) andmed ei ole ühises vormingus (suured/väikesed tähed, tühikud), mistõttu sama linn esineb mitmel erineval kujul. Esimene klient registreeriti 02.01.2020 ja uusim 27.02.2025. Viimase 6 kuu jooksul lisandus 325 uut klienti, mis moodustab 10,3% kogu kliendibaasist. Andmestik on piisavalt kvaliteetne edasiseks analüüsiks. Kuigi customer_id väärtused on unikaalsed, vajavad täiendavat kontrolli kliendiandmed (nt nimi ja email) ning vajalik on andmete korrastamine ja puuduvate väärtuste täitmine.

- **products**: 362 rida, 9 veergu

peamine leid : puuduvad 18 toote sertifikaadid ning 10l tootel on soetushind suurem kui müügihind. Tabelis võiks sisalduda ka kate (rahaline, protsent).

- **sales** (kanalid/asukohad): [unikaalsed kanalid, asukohad, peamine leid]

SUURIM ÜLLATUS :
[1-2 lauset]

SOOVITUS TOOMASELE :
[1-2 lauset]

PUUDUVAD ANDMED :
[1-2 lauset]
