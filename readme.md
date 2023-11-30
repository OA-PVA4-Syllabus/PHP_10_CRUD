# PVA4 - Programování a vývoj aplikací
## SQL-02 - DDL

## Obsah

Zdrojový kód SQL každého bloku uložte do souboru `sql_ddl_reseni_???.sql` místo otazníku použijte číslo zadání. Celkem odevzdáte 6 souborů.


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



### 3 Relace
Definujte mezi tabulkami správné relace


### 4 Vložení záznamů
* Sepište SQL příkaz pro vložení tří zaměstnanců.
* U dvou zaměstnanců definujte jednu adresu a u jednoho budou adresy dvě.
* Ke každému zaměstnanci nastavte alespoň tři záznamy do tabulky poměry.

### 5 Update
* Napište SQL script, který všem aktivním pracovníkům (aktuální datum je mezi zahájením a ukončením) zvýší mzdu o 2,5% 
* Pomocí sql scriptu upravte všem záznamům, které nemají vyplněn kód státu CZ.
  
### 6 Smazání
* SQL scriptem smažte všechny záznamy z tabulky poměry, které nemají vyplněné id zaměstnance nebo výši mzdy.

