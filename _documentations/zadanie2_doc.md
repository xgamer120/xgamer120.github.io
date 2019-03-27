---
short_name: z2
name: Zadanie 2 Dokumentacia
---
# Zadanie

Predmetom 2. zadania je spracovanie vybraného dokumentu (ideálne bakalárskeho projektu) z pôvodného ľubovoľného (Word, OpenOffice, LaTeX, …) formátu do formátu DocBook a vygenerovanie cieľového tvaru v PDF. Výsledný dokument bude mať rozsah minimálne 10 a maximálne 15 strán. Do rozsahu sa nezapočítavajú úvodné strany (obsah, zoznamy obrázkov a tabuliek), použitá literatúra a prílohy.

# Použité elementy a atribúty

## štandardné členenie textu na kapitola, podkapitola, podpodkapitola, príloha, generovaný obsah

* **chapter** - element pre označenie kapitoly
* **section** - označenie sekcie/podkapitoly, atribút *id* pre identifikáciu elementu
* **appendix** - vytvorenie dodatkov, pri dodatku použitý **variablelist**

## zvýraznenie slov, zvýraznenie členenia textu odrážkami alebo číslovaním

* **emphasis** - zvýraznenie textu kurzívou
* **itemizedlist** - členenie odrážkami, použitý atribút *mark* s hodnotou "bullet" pre odrážky v tvare vyplnenej guličky

## odkazy na iné časti vlastného dokumentu, prípadne odkazy na URL

* **ulink** - odkaz na url link
* **xref** - odkazovanie na iné časti dokumentu

## poznámka pod čiarou

* **footnote** - vytvorenie poznámky pod čiarou na konci strany

## zoznam použitej literatúry a zdrojov vrátane ich citácie v texte

* **bibliography** - vytvorenie zoznamu literatúri
* **bibliomixed** - element predstavuje jeden bibliografický záznam
* **bibliomisc** - vedľajšie informácie o knihe/článku 
* **xref** - odkaz na bibliografický záznam

## vloženie obrázku a tabuliek, odkazy na ne v texte; zoznam obrázkov a tabuliek v úvode alebo závere textu

* **figure** - predstavuje objekt s nadpisom a mediálnym objektom **mediaobject**, ktorý obsahuje audio, image, video alebo text objekt
* **table** - vytvorenie tabuľky, podobne ako v html
* **xref** - odkazovanie na obrázky a tabuľky, použitý atribút *xrefstyle* s hodnotou "style: label" pre odkaz iba cez označenie

* úprava thesis.xsl pre generovanie zoznamu obrázkov a tabuliek

## vytvorenie registra pojmov (indexu) s pojmami hierarchicky usporiadanými do dvoch úrovni, napríklad „cykly, while“, „cykly, for“ 

* **index** - vytvori samotny index
* **indexterm** - záznam do indexu, použité **primary** a **secondary** pre hierarchické rozdelenie s atribútom *sortas* pre zoskupenie
