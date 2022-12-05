# PVA4 - Programování a vývoj aplikací
## Lekce 10: CRUD operace

## Obsah

Zdrojový kód SQL uložte do souboru `databaze.sql`


### 1 Založení DB
Založte novou databázi `sandbox`


### 2 Tabulky
Vytvořte tabulky `zamestnanec` a `adresa` s níže uvedenými sloupci.

*Zaměstnanec*:
* jméno
* příjmení
* titul před
* titul za
* rodné číslo

*Adresa*
* druh adresy (např. trvalá nebo korespondenční)
* ulice
* popisné číslo
* město
* psč
* kód státu
  
*Poměry*
* mzda
* datum zahájení
* datum ukončení

Zdrojový kód SQL uložte do souboru `tabulka.sql`


### 3 Relace
Definujte mezi tabulkami správné relace


### 4 Vložení záznamů
* a) Sepište SQL příkaz pro vložení tří zaměstnanců.
* b) U dvou zaměstnanců definujte jednu adresu a u jednoho budou adresy dvě.
* c) Ke každému zaměstnanci nastavte alespoň dva tři záznamy do tabulky poměry.

### 5 Update
* a) Napište SQL script, který všem aktivním pracovníkům (aktuální datum je mezi zahájením a ukončením) zvýší mzdu o 2,5% 
* b) Pomocí sql scriptu upravte všem záznamům, které nemají vyplněn kód státu CZ.

### 6 Smazání
* a) SQL scriptem smažte všechny záznamy z tabulky poměry, které nemají vyplněné id zaměstnance nebo výši mzdy.

