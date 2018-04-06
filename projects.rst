Projekty
========

Typy projektů
-------------

Existují dva druhy projektů:

+--------------+-------------------------------------------------------+
| Type         | Description                                           |
+==============+=======================================================+
| Týmový       | Projekt s řízením uživatelů a skupin                  |
| projekt      |                                                       |
+--------------+-------------------------------------------------------+
| Soukromý     | Projekt, který patří pouze jedné osobě, nemá správu   |
| projekt      | uživatelů                                             |
+--------------+-------------------------------------------------------+

-  Pouze správci a aplikační správci mohou vytvářet týmové projekty.
-  Soukromé projekty může vytvářet každý.

Vytváření projektů
------------------

Kanboard dokáže zpracovat více projektů. Existují dva druhy projektů:

-  Týmové projekty
-  Soukromý projekt pro jednoho uživatele

Vytváření projektů pro více uživatelů
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  Tyto projekty mohou vytvářet pouze správci a správci projektů
-  Správa uživatelů je k dispozici

Na nástěnce klikněte na odkaz **Nový projekt**:

.. figure:: /_static/new-project.png
   :alt: Formulář pro tvorbu projektu

Je to velmi snadné: stačí najít jméno pro svůj projekt!

Vytváření soukromého projektu
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  Každý může vytvořit soukromý projekt
-  **Není** zde možnost správy uživatelů
-  Do projektu mohou přistupovat pouze vlastníci a správci

Na nástěnce klikněte na odkaz **Nový soukromý projekt**.

Vytváření projektů z jiného projektu
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Při vytváření nového projektu můžete zvolit duplikování vlastností
jiného projektu:

-  Oprávnění
-  Akce
-  Dráhy
-  Kategorie
-  Úkoly

Úpravy projektů
---------------

Projekty lze kdykoli přejmenovat nebo zakázat.

Chcete-li projekt přejmenovat, klikněte na odkaz “Upravit projekt”
vlevo.

.. figure:: /_static/project-edition.png
   :alt: Úprava projektu

-  Datum zahájení a datum ukončení se používají k vygenerování Ganttova
   grafu projektu.
-  Popis je viditelný jako nápověda na nástěnce a na stránce výpisů
   projektů.
-  Správci a správci projektů mohou převádět soukromý projekt na projekt
   s více uživateli změnou zaškrtávacího políčka “Soukromý projekt”.
-  Můžete také převést týmový projekt na soukromý projekt.

Poznámka: Když převedete projekt na soukromý, všichni stávající
uživatelé budou stále mít přístup k projektu. Seznam uživatelů můžete
upravit podle vašich potřeb.

Odstranění projektů
-------------------

Chcete-li projekt odebrat, musíte být správcem projektu nebo správcem.

Přejděte na položku **“Nastavení projektu”** a v nabídce vlevo, v dolní
části zvolte možnost “Odstranit”.

.. figure:: /_static/project-remove.png
   :alt: Odstranění projektů

Odstranění projektu odstraní všechny úkoly, které patří tomuto projektu.

Oprávnění projektu
------------------

Každý projekt je izolován od jiných projektů. Přístup k projektu musí
být povolen vlastníkem projektu.

Každý uživatel a každá skupina mohou mít přiřazenou jinou roli. Existují
3 typy rolí projektu:

-  Správce projektu
-  Člen projektu
-  Čtenář projektu

Pouze správci mají přístup ke všemu.

Přiřazení rolí je viditelné v **Nastavení projektu > Oprávnění**:

.. figure:: /_static/project-permissions.png
   :alt: Oprávnění projektu

U soukromých projektů nelze definovat oprávnění.
