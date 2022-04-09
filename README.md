# UTB---AK8PO
Pokročilé programování

# Projekt 

Budu zpraocvávat vzorový příklad na moodle, který bude lehce modifikovaný pro mé potřeby.
btw: Ve firmně hrajeme stolní tenis. Chci udělat jednoduchý systém pro evidenci hráčů, zápasů a skóre hráčů.

1) Scénář
Bude vytvořen systém na evidenci zápasů ve stolním tenisu, který bude řešit generování zá pasů dle přihlášených hráčů. Systém bude evidovat ligu, která je definovaná na určité období a je složena z x zápasů. Jednou za týden jsou vygenerovány zápasy z přihlášených hráčů. Systém vygeneruje vyvážené zápasy dle skóre hráčů. V průběhu ligy zobrazuje pořadí hráčů a jejich skóre. 

3) Požadavky v bodech
Evidence hráčů. Jméno a další volitelné info (foto, věk, pohlaví atd..)
Evidence zápasů. Kdo s kým hrál a jaký byl výsledek.
Generování zápasů dle přihlášených hráčů. 
Evidence a výpočet skóre jednotlivých hráčů.
Systém generování "vyvážených" zápasů (hráči s podobným skóre hrají spolu).
Přehledné zobrazení pořadí hráčů, včetně historického vývoje. 
Upozornění emailem na konaný zápas s definovaným předstihem.

5) Technologie
SQL, C#, Ještě nevím co zvolím (front end)  

7) Časový plán 
Kmpletní analýza požadavků. (8 hodin)
Analýza struktury a formy vyhodnocení zápasů (výpočtu skóre) a generování zápasu (4 hodiny)
Návrh datové struktury a DB. (8 hodin)
Výběr kompletních technologií (3 hodiny)
Programování back-end (+8 hodin)
Programování front-end (+8 hodin)
Generování upozorněnění (4 hodiny).

9) Otázky
Kdo se účastní ligy? 
Přihlášení hráči.

Jak se hráč přihlásí do ligy? 
Dostane odkaz na systém, kde se může registrovat.

Jak bude řešeno přihlášení? 
Jméno + Heslo.

Kdy a jak se generuje zápas? 
Admin systému spustí generování. Popřípadě pověřený uživatel. 

Co když hráč v systému nemůže hrát? 
Systém bude umožňovat hráči definovat "dovolenou" (dobu ve které nemůže hrát).

Jak nahlásím výsledke zápasu? 
Jeden z hráčů zápasu v systému nahlásí výsledek zápasu. Druhý hráč potvrdí výsledek. Pokud dojde se sporu tak bude admin, který to nějak vyřeší. 




