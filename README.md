# B2B czy etat 2026 (Otwarte dane CSV)

Zestawienie porównujące umowę o pracę (UoP) z jednoosobową działalnością gospodarczą B2B na Dużym ZUS w Polsce w 2026 roku dla miesięcznego budżetu firmy od 8 000 do 30 000 zł (co 1 000 zł).

Pełny raport z opisem metodologii, pułapek podatkowych i ukrytych ryzyk B2B znajduje się na stronie [kalkulatorfirmy.pl/raporty/b2b-vs-etat-2026/](https://kalkulatorfirmy.pl/raporty/b2b-vs-etat-2026/).

Plik danych: [`data/b2b-vs-etat-2026.csv`](data/b2b-vs-etat-2026.csv) (46 wierszy, kodowanie UTF-8: 23 progi budżetu w wariancie z 26 dniami niepłatnego urlopu i 500 zł kosztów oraz 23 progi dla pełnych 12 faktur bez kosztów).

---

## Najważniejsze wnioski z danych 2026

Wszystkie kwoty dotyczą parametrów ustawowych 2026 roku: Duży ZUS z dobrowolną składką chorobową (`1 926,76 zł/mies.`, podstawa `5 652 zł`), płaca minimalna `4 806 zł`, minimalna składka zdrowotna `432,54 zł`, progi zdrowotnej na ryczałcie `498,35 / 830,58 / 1 495,04 zł` oraz roczny limit odliczenia zdrowotnej na podatku liniowym `14 100 zł`.

1. **Do 13 000 zł budżetu firmy wygrywa umowa o pracę.** W wariancie z 26 dniami niepłatnego urlopu (z 252 dni roboczych w roku, czyli `-10,3%` przychodu) i 500 zł miesięcznych kosztów księgowości oraz sprzętu każda forma B2B na Dużym ZUS zostawia mniej gotówki niż UoP. Przy 10 000 zł budżetu etat daje `5 988,59 zł` netto, skala na B2B `5 467,76 zł` (`-520,83 zł/mies.`), a ryczałt 12% tylko `4 899,16 zł` (`-1 089,43 zł/mies.`).
2. **Próg opłacalności B2B zależy od stawki podatku.** Przy 26 niepłatnych dniach i 500 zł kosztów ryczałt 8,5% wyprzedza UoP od `14 000 zł` budżetu (`8 418,30 zł` wobec `8 251,63 zł`), ryczałt 12% od `15 000 zł` (`8 845,21 zł` wobec `8 817,38 zł`), ryczałt 15% od `17 000 zł` (`10 032,36 zł` wobec `9 948,91 zł`), a podatek liniowy 19% dopiero od `18 000 zł` (`10 565,68 zł` wobec `10 514,66 zł`).
3. **Niepłatny urlop i 500 zł kosztów zabierają ponad 2 100 zł miesięcznie przy średnich stawkach.** Przy budżecie `18 000 zł` na ryczałcie 12% pełne 12 faktur bez kosztów daje `13 347,08 zł/mies.`, natomiast wariant z 26 dniami wolnymi i 500 zł kosztów spada do `11 212,77 zł/mies.` (różnica `2 134,31 zł/mies.`, czyli `25 611,72 zł/rok`).
4. **Próg 300 000 zł rocznego przychodu na ryczałcie zjada większość podwyżki.** Po jego przekroczeniu składka zdrowotna rośnie z `830,58 zł` do `1 495,04 zł` za każdy miesiąc roku (`+7 973,52 zł/rok`). W wariancie z urlopem próg pęka między `29 000` a `30 000 zł` budżetu: na ryczałcie 12% podwyżka o 1 000 zł miesięcznie zostawia zaledwie `164,61 zł` więcej na rękę (`19 894,10 zł` -> `20 058,71 zł`). Przy pełnych 12 fakturach ten sam skok następuje między `26 000` a `27 000 zł` (`20 387,08 zł` -> `20 642,53 zł`, tylko `+255,45 zł/mies.`).

---

## 1. Wariant realny: 26 dni niepłatnego urlopu i 500 zł kosztów miesięcznie (`urlop_26_dni_koszty_500`)

Porównanie przy tym samym miesięcznym koszcie po stronie firmy (budżet pracodawcy na UoP obejmuje 20,48% narzutów ZUS pracodawcy bez PPK; po stronie B2B jest to kwota netto na fakturze przed korektą o 26 dni bez fakturowania).

| Budżet firmy | UoP brutto | UoP netto* | B2B skala | B2B liniowy | Ryczałt 8,5% | Ryczałt 12% | Ryczałt 15% | Najlepsze B2B vs UoP (mies.) |
|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 8 000 zł | 6 640,11 zł | 4 856,08 zł | 4 045,55 zł | 3 495,38 zł | 3 494,76 zł | 3 320,76 zł | 3 171,59 zł | -810,53 zł |
| 10 000 zł | 8 300,13 zł | 5 988,59 zł | 5 467,76 zł | 4 948,28 zł | 5 135,91 zł | 4 899,16 zł | 4 696,24 zł | -520,83 zł |
| 12 000 zł | 9 960,16 zł | 7 120,11 zł | 6 884,73 zł | 6 401,10 zł | 6 777,06 zł | 6 477,56 zł | 6 220,81 zł | -235,38 zł |
| 13 000 zł | 10 790,17 zł | 7 685,86 zł | 7 593,26 zł | 7 111,52 zł | 7 597,72 zł | 7 266,81 zł | 6 983,14 zł | -88,14 zł |
| 14 000 zł | 11 620,19 zł | 8 251,63 zł | 8 275,96 zł | 7 802,32 zł | 8 418,30 zł | 8 055,97 zł | 7 745,39 zł | +166,67 zł |
| 15 000 zł | 12 450,20 zł | 8 817,38 zł | 8 805,14 zł | 8 493,11 zł | 9 238,87 zł | 8 845,21 zł | 8 507,71 zł | +421,49 zł |
| 17 000 zł | 14 110,23 zł | 9 948,91 zł | 9 863,37 zł | 9 874,80 zł | 10 880,11 zł | 10 423,61 zł | 10 032,36 zł | +931,20 zł |
| 18 000 zł | 14 940,24 zł | 10 514,66 zł | 10 392,48 zł | 10 565,68 zł | 11 700,69 zł | 11 212,77 zł | 10 794,60 zł | +1 186,03 zł |
| 20 000 zł | 16 600,27 zł | 11 646,18 zł | 11 450,79 zł | 11 947,35 zł | 13 341,84 zł | 12 791,25 zł | 12 319,25 zł | +1 695,66 zł |
| 22 000 zł | 18 260,29 zł | 12 777,70 zł | 12 509,01 zł | 13 328,95 zł | 14 983,07 zł | 14 369,65 zł | 13 843,82 zł | +2 205,37 zł |
| 25 000 zł | 20 750,33 zł | 14 474,98 zł | 14 096,42 zł | 15 401,50 zł | 17 444,87 zł | 16 737,21 zł | 16 130,71 zł | +2 969,89 zł |
| 29 000 zł | 24 070,39 zł | 16 739,01 zł | 16 212,87 zł | 18 164,78 zł | 20 727,27 zł | 19 894,10 zł | 19 179,93 zł | +3 988,26 zł |
| 30 000 zł | 24 900,40 zł | 17 304,76 zł | 16 741,98 zł | 18 851,00 zł | 20 911,63 zł | 20 058,71 zł | 19 327,63 zł | +3 606,87 zł |

*\*Uwaga metodologiczna dla UoP: kolumna `uop_netto_pln` pokazuje miesięczną wypłatę w pierwszym progu 12% PIT (PIT-2, podstawowe KUP 250 zł, bez PPK). Powyżej ok. 12 000 zł brutto miesięcznie pracownik wchodzi w trakcie roku w drugi próg 32% PIT, co dodatkowo obniża średnią roczną pensję netto na etacie i zwiększa przewagę B2B.*

---

## 2. Wariant pełnych 12 faktur bez kosztów (`pelne_12_mies_koszty_0`)

Wariant odpowiada kontraktowi z płatną przerwą w świadczeniu usług (0 dni bez fakturowania) i brakiem dodatkowych kosztów po stronie zleceniobiorcy.

| Budżet firmy | UoP netto* | B2B skala | B2B liniowy | Ryczałt 8,5% | Ryczałt 12% | Ryczałt 15% | Najlepsze B2B vs UoP (rok) |
|---:|---:|---:|---:|---:|---:|---:|---:|
| 8 000 zł | 4 856,08 zł | 5 097,90 zł | 4 568,95 zł | 4 749,99 zł | 4 547,08 zł | 4 373,16 zł | +2 901,84 zł |
| 10 000 zł | 5 988,59 zł | 6 677,90 zł | 6 188,95 zł | 6 579,99 zł | 6 307,08 zł | 6 073,16 zł | +8 271,72 zł |
| 14 000 zł | 8 251,63 zł | 9 423,23 zł | 9 300,15 zł | 10 239,99 zł | 9 827,08 zł | 9 473,16 zł | +23 860,32 zł |
| 18 000 zł | 10 514,66 zł | 11 783,23 zł | 12 381,40 zł | 13 899,99 zł | 13 347,08 zł | 12 873,16 zł | +40 623,96 zł |
| 22 000 zł | 12 777,70 zł | 14 143,23 zł | 15 462,65 zł | 17 559,99 zł | 16 867,08 zł | 16 273,16 zł | +57 387,48 zł |
| 26 000 zł | 15 040,73 zł | 16 503,23 zł | 18 542,98 zł | 21 219,99 zł | 20 387,08 zł | 19 673,16 zł | +74 151,12 zł |
| 27 000 zł | 15 606,49 zł | 17 093,23 zł | 19 303,98 zł | 21 498,78 zł | 20 642,53 zł | 19 908,53 zł | +70 707,48 zł |
| 30 000 zł | 17 304,76 zł | 18 863,23 zł | 21 586,98 zł | 24 243,78 zł | 23 282,53 zł | 22 458,53 zł | +83 268,24 zł |

Pełne 46 wierszy (co 1 000 zł od 8 000 do 30 000 zł w obu scenariuszach) znajduje się w [`data/b2b-vs-etat-2026.csv`](data/b2b-vs-etat-2026.csv).

---

## Słownik kolumn (`data/b2b-vs-etat-2026.csv`)

- `scenariusz`: Nazwa wariantu założeń (`urlop_26_dni_koszty_500` lub `pelne_12_mies_koszty_0`).
- `budzet_mies_pln`: Miesięczny budżet pracodawcy w PLN (pełny koszt UoP równy kwocie netto faktury B2B przy pełnym miesiącu).
- `uop_brutto_pln`: Pensja brutto na umowie o pracę odpowiadająca temu budżetowi (po odjęciu 20,48% składek ZUS pracodawcy, bez PPK).
- `uop_netto_pln`: Miesięczna wypłata na rękę na UoP w pierwszym progu 12% PIT (PIT-2, KUP 250 zł, bez PPK).
- `b2b_realny_przychod_mies_pln`: Średni miesięczny przychód netto na B2B po uwzględnieniu niepłatnych dni urlopu (`budzet * (252 - dni_wolne) / 252`).
- `b2b_koszty_mies_pln`: Miesięczne koszty prowadzenia działalności (księgowość, sprzęt, oprogramowanie) w PLN.
- `b2b_zus_spoleczne_pln`: Miesięczne składki społeczne ZUS i Fundusz Pracy dla Dużego ZUS z chorobowym w 2026 r. (`1 926,76 zł`).
- `b2b_skala_netto_pln`: Miesięczna kwota na rękę na B2B przy opodatkowaniu skalą podatkową (12% / 32%, zdrowotna 9%).
- `b2b_liniowy_netto_pln`: Miesięczna kwota na rękę na B2B przy podatku liniowym 19% (zdrowotna 4,9%, limit odliczenia 14 100 zł/rok).
- `b2b_ryczalt_8_5_netto_pln`: Miesięczna kwota na rękę na ryczałcie 8,5% (z uwzględnieniem progów zdrowotnej i odliczenia 50% zdrowotnej).
- `b2b_ryczalt_12_netto_pln`: Miesięczna kwota na rękę na ryczałcie 12% (np. programowanie i wdrażanie oprogramowania).
- `b2b_ryczalt_15_netto_pln`: Miesięczna kwota na rękę na ryczałcie 15% (np. część usług doradczych, licencyjnych, zarządczych).
- `najkorzystniejsza_forma_b2b`: Forma opodatkowania B2B z najwyższą kwotą na rękę spośród pięciu wariantów (`skala` lub `ryczalt_8_5`).
- `roznica_najlepsze_b2b_vs_uop_mies_pln`: Różnica miesięczna (PLN) między najwyższą kwotą na rękę na B2B a `uop_netto_pln`.
- `roznica_najlepsze_b2b_vs_uop_rok_pln`: Różnica roczna (12 × różnica miesięczna) w PLN.

---

## Podstawy prawne (stan na 2026 r.) i kalkulatory online

Źródła ustawowe:
- Ustawa o podatku dochodowym od osób fizycznych (`Dz.U. z 2026 r. poz. 592`): https://isap.sejm.gov.pl/isap.nsf/DocDetails.xsp?id=WDU19910800350
- Ustawa o zryczałtowanym podatku dochodowym (`Dz.U. z 2025 r. poz. 843`): https://isap.sejm.gov.pl/isap.nsf/DocDetails.xsp?id=WDU19981440930
- Ustawa o systemie ubezpieczeń społecznych (`Dz.U. z 2026 r. poz. 1474`): https://isap.sejm.gov.pl/isap.nsf/DocDetails.xsp?id=WDU19981370887
- Ustawa o świadczeniach opieki zdrowotnej finansowanych ze środków publicznych (`Dz.U. z 2025 r. poz. 1461`): https://isap.sejm.gov.pl/isap.nsf/DocDetails.xsp?id=WDU20042102135
- Kodeks pracy (`Dz.U. z 2026 r. poz. 1245`, w tym art. 302¹ dot. stażu pracy JDG): https://isap.sejm.gov.pl/isap.nsf/DocDetails.xsp?id=WDU19740240141

Narzędzia i raport na KalkulatorFirmy.pl:
- Pełny raport B2B vs etat 2026: https://kalkulatorfirmy.pl/raporty/b2b-vs-etat-2026/
- Kalkulator B2B 2026 (skala, liniowy, ryczałt, Ulga na start, Preferencyjny i Mały ZUS Plus): https://kalkulatorfirmy.pl/b2b/kalkulator/
- Porównywarka własnej oferty B2B czy UoP: https://kalkulatorfirmy.pl/b2b/b2b-czy-uop/
- Darmowy widżet B2B do osadzenia na blogach i portalach kadrowych (iframe): https://kalkulatorfirmy.pl/embed/b2b/

## Licencja i cytowanie

Dane i dokumentacja są udostępniane na licencji [Creative Commons Attribution 4.0 International (CC-BY-4.0)](LICENSE).

Możesz dowolnie cytować tabele i tworzyć wykresy pod warunkiem podania źródła **KalkulatorFirmy.pl** (`https://kalkulatorfirmy.pl/raporty/b2b-vs-etat-2026/`). Metadane cytowania znajdują się w [`CITATION.cff`](CITATION.cff).

```text
KalkulatorFirmy.pl (2026). B2B czy etat 2026 (Polska): Progi opłacalności i realna wypłata na rękę na Dużym ZUS [Dataset]. https://kalkulatorfirmy.pl/raporty/b2b-vs-etat-2026/ (CC-BY-4.0).
```
