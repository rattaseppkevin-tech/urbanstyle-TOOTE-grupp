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

- **customers**: [X rida, Y veergu, peamine leid]

- **products**: 362 rida, 9 veergu

peamine leid : puuduvad 18 toote sertifikaadid ning 10l tootel on soetushind suurem kui müügihind. Tabelis võiks sisalduda ka kate (rahaline, protsent).

- **sales** (kanalid/asukohad): [unikaalsed kanalid, asukohad, peamine leid]

SUURIM ÜLLATUS :
[1-2 lauset]

SOOVITUS TOOMASELE :
[1-2 lauset]

PUUDUVAD ANDMED :
[1-2 lauset]
