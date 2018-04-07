Úkoly
=====

Vytváření úkolů
---------------

Na nástěnce klikněte na znaménko plus vedle názvu sloupce:

.. figure:: /_static/task-creation-board.png
   :alt: Vytváření úkolů z nástěnky

Poté se zobrazí formulář vytvoření úkolu:

.. figure:: /_static/task-creation-form.png
   :alt: Formulář pro tvorbu úkolů

Popis pole:

-  **Název**: Název vašeho úkolu, který bude zobrazen na nástěnce.
-  **Popis**: Popis, který používá formát Markdown.
-  **Štítky**: Seznam štítků přidružených k úkolům.
-  **Vytvoření dalšího úkolu**: Zaškrtněte toto políčko, pokud chcete
   vytvořit podobný úkol (některé pole budou předem naplněny).
-  **Barva**: Vyberte barvu karty.
-  **Vlastník**: Osoba, která bude na úkolu pracovat.
-  **Kategorie**: K úloze lze přiřadit pouze jednu kategorii (viditelné
   pouze v případě, že projekty mají kategorie).
-  **Sloupec**: Sloupec, ve kterém bude úloha vytvořena, úkol bude
   umístěn v dolní části.
-  **Priorita**: Priorita úkolu, rozsah lze definovat v nastavení
   projektu, výchozí hodnoty jsou P0 až P3.
-  **Složitost**: Používá se v agilním řízení projektů (Scrum),
   složitost nebo tzv. “story-points”, to je číslo, které říká týmu, jak
   těžký je úkol. Často lidé používají Fibonacciho posloupnost.
-  **Reference**: Externí ID úkolu, např. to může být číslo ticketu,
   které pochází z jiného systému
-  **Časový odhad**: Odhad v hodinách pro dokončení úkolu.
-  **Čas strávený**: Doba strávená při práci na úkolu.
-  **Datum zahájení**: Toto je pole pro zadání data a času zahájení.
-  **Datum splnění**: Opakované úkoly budou mít červený termín splnění a
   nadcházející termíny budou černé na nástěnce. Pro zadání datumů je k
   dispozici několik formátů datumu.

Pomocí odkazu náhled můžete vidět popis úlohy převedený ze syntaxe
Markdown.

Kopírovat a přesunout úkoly
---------------------------

Kopírovat úkol do stejného projektu
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Přejděte do zobrazení úkolů a vlevo vyberte položku **Vytvořit kopii**.

.. figure:: /_static/task-duplication.png
   :alt: Kopírování úloh

Nový úkol bude vytvořen se stejnými vlastnostmi jako originál.

Kopírovat úkol do jiného projektu
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Přejděte do zobrazení úkolů a vyberte možnost **Vytvořit kopii v jiném
projektu**.

.. figure:: /_static/task-duplication-another-project.png
   :alt: Kopírování úkolů do jiného projektu

V rozbalovací nabídce se zobrazí pouze projekty, ve kterých jste členem.

Než provedete kopírování úkolů, Kanboard se vás zeptá na cílové
vlastnosti, které nejsou společné mezi zdrojovým a cílovým projektem.

V zásadě musíte definovat:

-  cílová dráha
-  Sloupec
-  Kategorie
-  Vlastník

Přesunout úkol do jiného projektu
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Přejděte do zobrazení úkolů a vyberte možnost **Přesunout do jiného
projektu**.

Přesunutí úkolu do jiného projektu pracuje stejným způsobem jako
kopírování, musíte zvolit nové vlastnosti úkolu.

Seznam kopírovaných polí
~~~~~~~~~~~~~~~~~~~~~~~~

Zde je seznam kopírovaných vlastností:

-  název
-  popis
-  datum splnění
-  barva
-  projekt
-  sloupec
-  vlastník
-  skóre
-  kategorie
-  strávený čas
-  dráha
-  stav opakování
-  spouštěč opakování
-  faktor pro opakování
-  časové okno pro opakování
-  výchozí datum pro výpočet opakování

Uzavírání úkolů
---------------

Když je úkol uzavřen, je skrytý z nástěnky.

Vždy však můžete získat přístup k seznamu uzavřených úkolů pomocí dotazu
**status:closed** v libovolném vyhledávacím formuláři nebo jednoduše
vybrat **Uzavřené úkoly** z rozevírací nabídky filtru.

Existují dva různé způsoby jak zavřít úkol z rozbalovací nabídky úloh na
nástěnce:

.. figure:: /_static/menu-close-task.png
   :alt: Uzavřít úkol z rozbalovací nabídky

Nebo z nabídky postranního panelu úloh v detailním zobrazení úkolu:

.. figure:: /_static/closing-tasks.png
   :alt: Uzavřít úkol

Poznámka: Když zavřete úkol, všechny dílčí úkoly, které nebyly
dokončeny, budou změněny na stav “Dokončeno”.
