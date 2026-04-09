# Andmekvaliteedi Koondraport — Nädal 2

**Meeskond:** Tooteanalüüsi osakond
**Tegelane:** Toomas Kask
**Kuupäev:** 09.04.2026

## Peamised leiud

| Domeen | Roll | Leitud probleeme | Kirjeldus |
|--------|------|-----------------|-----------|
| Müük (sales) | Eike | 6612 | 5116 duplikaati (33,58%), 1487 NULL customer_id, 9 tuleviku kuupäeva |
| Kliendid (customers) | Krista | 699 | 129 duplikaat-emaili, 147 duplikaat-telefoni, 43 ebajärjekindlat linnанime, 380 NULL emaili |
| Tooted (products) | Egle | 12 | 12 duplikaаtnime, kriitilised väljad korras |
| Ristvalideerimine | Kevin | 1268 | 664 hinna ebakõla (kriitiline!), 592 vaimklienti, 12 müümata toodet |

## Suurim üllatus
Müügiandmetest 33,58% olid duplikaadid — see moonutab kogu käibearuandlust.

## Soovitus Toomasele
Kriitilisim domeen on müük (5116 duplikaati) ja hinnaebakõlad (664 rida) — alustada tuleb nende puhastamisest enne juhatuse koosolekut.

## Puuduvad andmed
988 tehingul puudub kliendi seos — ei tea, kes need kliendid on ja kas nad on lojaalsed.

## Esitlus
[Vaata esitlust PDF-ina](week2_team_cleaning_report.pdf)
