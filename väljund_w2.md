# Andmekvaliteedi Koondraport — Nädal 2

**Meeskond:** Tooteanalüüsi osakond
**Tegelane:** Toomas Kask
**Kuupäev:** 09.04.2026

## Peamised leiud

### Müük — Eike (Roll A)

| Kategooria | Leitud probleeme | Kirjeldus |
|------------|-----------------|-----------|
| Duplikaadid | 5116 (33,58%) | Korduvad sale_id väärtused |
| NULL customer_id | 1487 | Puuduv kliendi viide |
| NULL sale_date | 0 | Kontrollitud — puudujääke ei esinenud |
| NULL total_price | 0 | Kontrollitud — kõikidel tehingutel oli summa |
| Tuleviku kuupäevad | 9 | Kuupäev > tänane |
| **KOKKU** | **6612** | |

**Enne/pärast:** 15 234 → 10 118 rida (eemaldatud 5 116 duplikaati)

### Kliendid — Krista (Roll B)

| Kategooria | Leitud probleeme | Kirjeldus |
|------------|-----------------|-----------|
| Duplikaatsed e-mailid | 129 | Sama e-mail mitmel kliendil |
| Duplikaatsed telefonid | 147 | Sama telefon mitmel kliendil |
| NULL eesnimi | 0 | Kontrollitud — puudujääke ei esinenud |
| NULL perenimi | 0 | Kontrollitud — puudujääke ei esinenud |
| Ebajärjekindlad linnanimed | 43 | Nt tallinn vs TALLINN |
| NULL telefon/e-mail | 0/380 | E-mail puudub 380 kliendil |
| **KOKKU** | **699** | |

### Tooted — Egle (Roll C)

| Kategooria | Leitud probleeme | Kirjeldus |
|------------|-----------------|-----------|
| Duplikaatsed nimed | 12 | Sama tootenimi mitu korda |
| NULL nimi/hind | 0 | Kontrollitud — kriitilised väljad korras |
| Loogilised vead | 0 | Kontrollitud — negatiivseid hindu ei esine |
| Ebajärjekindlad kategooriad | 0 | Kontrollitud — puudujääke ei esinenud |
| NULL bränd/kategooria | 0 | Kontrollitud — puuduv klassifitseerimine puudub |
| **KOKKU** | **12** | |

### Ristvalideerimine — Kevin (Roll D)

| Kategooria | Leitud probleeme | Kirjeldus |
|------------|-----------------|-----------|
| Orbid kliendid | 0 | Kontrollitud — müük viitab olemasolevale kliendile |
| Orbid tooted | 0 | Kontrollitud — müük viitab olemasolevale tootele |
| Hinna ebakõlad | 664 | Müügihind ei klapi tootehinnaga (kriitiline!) |
| Vaimkliendid | 592 | Klient ei ole kunagi ostnud |
| Vaimtooted | 12 | Toodet pole kunagi müüdud |
| **KOKKU** | **1268** | |

## Suurim üllatus
Müügiandmetest 33,58% olid duplikaadid — see moonutab kogu käibearuandlust.

## Soovitus Toomasele
Kriitilisim domeen on müük (5116 duplikaati) ja hinnaebakõlad (664 rida) — alustada tuleb nende puhastamisest enne juhatuse koosolekut.

## Puuduvad andmed
988 tehingul puudub kliendi seos — ei tea, kes need kliendid on ja kas nad on lojaalsed.

## Esitlus
[Vaata esitlust PDF-ina](week2_team_cleaning_report.pdf)
