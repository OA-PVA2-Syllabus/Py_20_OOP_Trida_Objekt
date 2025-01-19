# PVA2 - Programování a vývoj aplikací
## Cvičení 20: OOP - Třída a Objekt

## Obsah

### 1 Student
Chcete vytvořit informační systém pro evidenci studentů.
Vytvořte třídu `Student`, definujte property `jméno`, `příjmení`, `třída`, `skupina`, `status` (boolean). True pro stav studenta, false pro uchazeče.

Definujte dvě instance objektu třídy student. Pro první instanci použijte své údaje.


### 2 Autopůjčovna
Vytvoř program pro evidenci aut malé autopůjčovny. Půjčovna má níže automobily:

| Registrační značka | Značka a typ vozidla | Počet najetých kilometrů  |
| ------------- |-------------| -----:|
| 4O2 1022 | Mercedes CLA 45s AMG 4MATIC Speedshift | 17534 |
| 4K8 7107 | Mercedes GLE 450 AMG Line 4MATIC |   31223 |
| POR911C |Porsche 911 Carrera 4S |   15 |

Vytvoř třídu `Auto`, která bude obsahovat informace o autech, které půjčovna nabízí. Třída bude mít tyto atributy:

- registrační značka automobilu,
- značka a typ vozidla,
- počet najetých kilometrů,
- informaci o tom, jestli je vozidlo aktuálně volné (pravdivostní hodnota -- True pokud je volné a False pokud je vypůjčené).

Definuj objekty vozidel a vypiš všechny ve formě tabulky.


### 3 Kino
Vytvoř program pro evidenci filmového promítání. Vytvořte třídu `film`, která bude mít atributy
- název filmu
- režisér
- rok vydání
- hodnocení na škále 1-10 (10 nejlepší)
- délka filmu
- cena lístku

Definuj alespoň tři objekty instance třídy. Pomocí cyklu zobrazte informace objektu o každém filmu.
