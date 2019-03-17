---
short_name: z1
name: Zadanie 1 Dokumentacia
---
# Zadanie

Vytvorte webovú prezentáciu (webové sídlo) o sebe. Zamerajte sa jednak na vaše profesné záujmy (napr. projekty, ktoré riešite/riešili ste, čo vás v informatike najviac baví, fascinuje = váš developerský profil) a jednak vaše osobné záujmy, hobby.

V rámci developerského profilu vytvorte sekciu Webové publikovanie, kde budete publikovať všetky tri vaše vypracované zadania z predmetu.

Využite pritom technológie Git + GitHub Pages + Jekyll + Markdown. Využite potenciál statického generátora Jekyll a jeho templatovacích možností.

# Rozlozenie stranok

Webové sídlo tvorí 5 hlavných podstránok a to domovská stránka, kde sú vypísané novinky na stránke, stránka o mojom developerskom profile, stránka s projektami na ktorych som pracoval, stránka so zadaniami s predmetu weboové publikovanie a stránka s dokumentáciami.

## Šablóny

* **default** je základná šablóna obsahujúca HTML hlavičku a skripty
* **documentation** je šablóna pre zobrazenie dokumentácie zadaní
* **projekt** je šablóna pre zobrazenie informácií o konkrétnom projekte
* **zadanie** je šablóna zobrazujúca informácie o zadaní s prílohami

## Použité prvky

* **premenné** použité su základné premenné ako name alebo title, premenná dokumentácia pri zadaniach urcuje oznacenie dokumentácie patriacej danemu zadaniu, ktore je v dokumentacii ulozene v premennej short_name
* **kolekcie** projekty, zadania, novinky a dokumentácie sú uložené v príslušných kolekciách
* **dátové súbory** pre jednoduchú úpravu navigácie stránky je vytvorený dátový súbor obsahujúci názvy podstránok a cestu k nim
* **filtre a tagy** filtrovanie dokumentácií pre nájdenie príslušnej dokumentácie, includovanie navigačného baru, zobrazenie dátumu, úprava textu
* **plugin** jednoduchý plugin pre pridávanie youtube videí
