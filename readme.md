---
archetype: "home"
title: "IFM 2.1: Programmieren 2 (Sommer 2024)"
---


> ... And, lastly, there's the explosive growth in demand, which has led to many
> people doing it who aren't any good at it. Code is merely a means to an end.
> **Programming is an art and code is merely its medium.**
> Pointing a camera at a subject does not make one a proper photographer. There are
> a lot of self-described coders out there who couldn't program their way out of a
> paper bag.
>
> \hfill -- John Gruber auf [daringfireball.net](https://daringfireball.net/2020/04/cobol_programming_coding)


## Kursbeschreibung

Sie haben letztes Semester in **Prog1** die _wichtigsten_ Elemente und Konzepte der
Programmiersprache Java kennen gelernt.

In diesem Modul geht es darum, diese Kenntnisse sowohl auf der Java- als auch auf der
Methoden-Seite so zu erweitern, dass Sie gemeinsam größere Anwendungen erstellen und
pflegen können. Sie werden fortgeschrittene Konzepte in Java kennenlernen und sich mit
etablierten Methoden in der Softwareentwicklung wie Versionierung von Code, Einhaltung
von Coding Conventions, Grundlagen des Softwaretests, Anwendung von Refactoring, Einsatz
von Build-Tools und Logging auseinander setzen. Wenn uns dabei ein Entwurfsmuster "über
den Weg läuft", werden wir die Gelegenheit nutzen und uns dieses genauer anschauen.


## Überblick Modulinhalte

1.  Fortgeschrittene Konzepte in Java
    *   Funktionale Programmierung: Default-Methoden, Funktionsinterfaces, Methodenreferenzen, Lambdas, Stream-API
    *   Generische Programmierung: Generics
    *   Parallele Programmierung: Threads
    *   Reguläre Ausdrücke, Annotationen, Reflection
    *   CLI, Konfiguration, Fremde APIs nutzen
2.  Fortgeschrittenes OO-Design
    *   Entwurfsmuster: Strategy, Template-Method, Factory-Method, Singleton, Observer, Visitor, Command, ...
3.  Programmiermethoden
    *   Versionskontrolle: Git
    *   Testen, Coding Conventions, Refactoring
    *   Logging, Build-Tools, CI


## Team

*   [Carsten Gips](https://www.hsbi.de/minden/ueber-uns/personenverzeichnis/carsten-gips) (Sprechstunde nach Vereinbarung per EMail)
*   Tutoren (siehe ILIAS-Mitgliederliste)


## Kursformat

:::::: {.tabs groupid="vl-pr"}
::: {.tab title="Vorlesung"}

**Vorlesung (2 SWS)**

Fr, 16:30 - 18:00 Uhr (online/J104)

:::
::: {.tab title="Praktikum"}

**Praktikum (2+1 SWS)**

| Praktikumsgruppe | Zeit                  | Raum        |
|:-----------------|:----------------------|:------------|
| Gruppe 1         | Fr, 09:00 - 10:30 Uhr | online/J104 |
| Gruppe 2         | Fr, 13:30 - 15:00 Uhr | online/J104 |
| Gruppe 3         | Fr, 15:00 - 16:30 Uhr | online/J104 |
| Gruppe 4         | Fr, 10:45 - 12:15 Uhr | online/J104 |

:::
::::::

Durchführung als **Flipped Classroom**:
Alle Sitzungen online/per Zoom (**Zugangsdaten siehe [ILIAS]**)

[ILIAS]: https://www.hsbi.de/elearning/goto.php?target=crs_1181185&client_id=FH-Bielefeld


## Prüfungsform, Note und Credits

**Parcoursprüfung**, 5 ECTS (PO23)

*   **Praktische Teilleistung**:
    Regelmäßige Bearbeitung der Praktikumsaufgaben,
    fristgerechte Abgabe der Lösungen (PDF, ZIP, Link) im ILIAS,
    Erstellung von Peer-Feedback im ILIAS,
    Vorstellung der Lösungen im Praktikum => Punkte

    Notenspiegel:
    *   90 Punkte gesamt erreichbar: Zyklus 1 und 2 je 15 Punkte, Zyklus 3 bis 5 je 15+5 Punkte
    *   4.0: ab 50% (45.0 Punkte), alle 5% nächste Teilnote, 1.0: ab 95% (85.5 Punkte)

*   **Theoretische Teilleistung**:
    Digitale Klausur ("**Klausur**") in den Prüfungszeiträumen; [Prüfungsvorbereitung](admin/exams.md).

*   **Gesamtnote**:
    50% Praxis, 50% Theorie

Wiederholer mit bereits begonnener Parcours-Prüfung absolvieren stattdessen eine Parcours-Prüfung.
Bitte melden Sie sich vor Beginn der Praktika per E-Mail beim Dozenten.


## Materialien

### Literatur

1.  ["**Java ist auch eine Insel**"](https://openbook.rheinwerk-verlag.de/javainsel/index.html).
    Ullenboom, C., Rheinwerk-Verlag, 2021.
    ISBN [978-3-8362-8745-6](https://fhb-bielefeld.digibib.net/openurl?isbn=978-3-8362-8745-6).
2.  ["**Pro Git** (Second Edition)"](https://git-scm.com/book/en/v2).
    Chacon, S. und Straub, B., Apress, 2014.
    ISBN [978-1-4842-0077-3](https://fhb-bielefeld.digibib.net/openurl?isbn=978-1-4842-0077-3).
3.  ["The Java Tutorials"](https://docs.oracle.com/javase/tutorial/).
    Oracle Corporation, 2023.
4.  ["Learn Java"](https://dev.java/learn/).
    Oracle Corporation, 2023.

### Tools

*   JDK: Java SE 21 (LTS) ([Oracle](https://www.oracle.com/java/technologies/downloads/) oder
    [Alternativen](https://code.visualstudio.com/docs/languages/java#_install-a-java-development-kit-jdk),
    bitte 64-bit Version nutzen)
*   IDE: [Eclipse IDE for Java Developers](https://www.eclipse.org/downloads/) oder
    [IntelliJ IDEA (Community Edition)](https://www.jetbrains.com/idea/) oder
    [Visual Studio Code](https://code.visualstudio.com/) oder [Vim](https://www.vim.org/) oder ...
*   [Git](https://git-scm.com/)


## Fahrplan

:::::: {.tabs groupid="vl-pr"}
::: {.tab title="Vorlesung"}

| Woche | Datum Vorlesung                           | Themen                                                                                                                       | Bemerkungen                                                                                      |
|:-----:|:------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------|
|  15   | Fr, 14.04.                                | Orga (**Zoom**) \|\| [Einführung Versionierung] \| [Git Basics] \|\| [Lambda-Ausdrücke] \|\| [Javadoc]                       |                                                                                                  |
|  16   | Fr, 21.04.                                | Git: [Branches] \| [Branching-Strategies] \|\| [Gradle] \|\| [Methodenreferenzen] \|\| [Strategy-Pattern]                    |                                                                                                  |
|  17   | Fr, 28.04.                                | Git: [Remotes] \| [Workflows] \|\| [Stream-API] \| [Optional]                                                                |                                                                                                  |
|  18   | Fr, 05.05.                                | Testen: [Einführung] \| [JUnit-Basics] \| [Testfallermittlung] \| [Mocking] \|\| [Logging]                                   |                                                                                                  |
|  19   | Fr, 12.05.                                | [Code-Smells] \| [Coding-Rules] \| [Refactoring] \|\| [CI]                                                                   | **Gastvortrag zu JUnit/Mocking in der Praxis von Daniel Rosowski (Smartsquare GmbH, Bielefeld)** |
|  20   | Fr, 19.05.                                | [Serialisierung] \|\| [Records] \| [Default-Methoden] \|\| [Docker] \|\| [Git-Worktree]                                      |                                                                                                  |
|  21   | Fr, 26.05.                                | Generics: [Klassen und Methoden] \| [Bounds und Wildcards] \| [Type Erasure] \| [Polymorphie] \|\| [Collections]             |                                                                                                  |
|  22   | Fr, 02.06.                                | [RegExp] \|\| Pattern: [Visitor] \| [Observer] \| [Command]                                                                  |                                                                                                  |
|  23   | Fr, 09.06.                                | [Annotationen] \| [Reflection] \| [Exception-Handling] \|\| [Singleton-Pattern]                                              |                                                                                                  |
|  24   | Fr, 16.06.                                | [Enumerationen] \| [Konfiguration] \| [ANT] \|\| [Template-Method-Pattern] \| [Factory-Method-Pattern]                       |                                                                                                  |
|  25   | Fr, 23.06.                                | Multi-Threading: [Intro Threads] \| [Synchronisierung] \| [Highlevel Threadkonzepte] \|\| [Maven] \|\| [Type-Object-Pattern] |                                                                                                  |
|  26   | Fr, 30.06.                                | Rückblick (**Zoom**) \| [Prüfungsvorbereitung]                                                                               |                                                                                                  |
| _27_  | _Mi, 05.07._ (Start: 09:00 und 11:00 Uhr) | Klausur (Campus Minden, B40)                                                                                                 |                                                                                                  |

[Prüfungsvorbereitung]: admin/exams.md

[Gradle]: lecture/building/gradle.md
[ANT]: lecture/building/ant.md
[Maven]: lecture/building/maven.md
[CI]: lecture/building/ci.md
[Docker]: lecture/building/docker.md

[Javadoc]: lecture/coding/javadoc.md
[Logging]: lecture/coding/logging.md
[Code-Smells]: lecture/coding/smells.md
[Coding-Rules]: lecture/coding/codingrules.md
[Refactoring]: lecture/coding/refactoring.md
<!-- [Debugging]: lecture/coding/debugging.md -->
<!-- [TDD]: lecture/coding/tdd.md -->

<!-- [JDBC]: lecture/database/jdbc.md  -->

<!-- [Intro Frameworks]: lecture/frameworks/intro-frameworks.md -->
<!-- [ECS]: lecture/frameworks/ecs.md -->
<!-- [Dungeon]: lecture/frameworks/dungeon.md -->

[Klassen und Methoden]: lecture/generics/classes-methods.md
[Bounds und Wildcards]: lecture/generics/bounds-wildcards.md
[Type Erasure]: lecture/generics/type-erasure.md
[Polymorphie]: lecture/generics/generics-polymorphism.md

[Einführung Versionierung]: lecture/git/git-intro.md
[Git Basics]: lecture/git/git-basics.md
[Branches]: lecture/git/branches.md
[Branching-Strategies]: lecture/git/branching-strategies.md
[Remotes]: lecture/git/remotes.md
[Workflows]: lecture/git/workflows.md
[Git-Worktree]: lecture/git/worktree.md
<!-- [Git-Bisect]: lecture/git/bisect.md -->

<!-- [Swing Basics]: lecture/gui/swing-basics.md -->
<!-- [Swing Widgets]: lecture/gui/widgets.md -->
<!-- [Layout Manager]: lecture/gui/layouts.md -->
<!-- [Swing Events]: lecture/gui/events.md -->
<!-- [Swing: Tabellen]: lecture/gui/tables.md -->
<!-- [Java2D]: lecture/gui/java2d.md -->

[Serialisierung]: lecture/java-jvm/serialisation.md
[Collections]: lecture/java-jvm/collections.md
[RegExp]: lecture/java-jvm/regexp.md
[Annotationen]: lecture/java-jvm/annotations.md
[Reflection]: lecture/java-jvm/reflection.md
[Exception-Handling]: lecture/java-jvm/exceptions.md
[Enumerationen]: lecture/java-jvm/enums.md
[Konfiguration]: lecture/java-jvm/configuration.md

[Lambda-Ausdrücke]: lecture/modern-java/lambdas.md
[Methodenreferenzen]: lecture/modern-java/methodreferences.md
[Stream-API]: lecture/modern-java/stream-api.md
[Optional]: lecture/modern-java/optional.md
[Records]: lecture/modern-java/records.md
[Default-Methoden]: lecture/modern-java/defaultmethods.md
<!-- [Sealed Classes]: lecture/modern-java/sealed.md -->

[Strategy-Pattern]: lecture/pattern/strategy.md
[Visitor]: lecture/pattern/visitor.md
[Observer]: lecture/pattern/observer.md
[Command]: lecture/pattern/command.md
[Singleton-Pattern]: lecture/pattern/singleton.md
[Template-Method-Pattern]: lecture/pattern/template-method.md
[Factory-Method-Pattern]: lecture/pattern/factory-method.md
[Type-Object-Pattern]: lecture/pattern/type-object.md
<!-- [Flyweight-Pattern]: lecture/pattern/flyweight.md -->
<!-- [Dependency Injection]: lecture/pattern/dependency.md -->

[Einführung]: lecture/testing/testing-intro.md
[JUnit-Basics]: lecture/testing/junit-basics.md
[Testfallermittlung]: lecture/testing/testcases.md
[Mocking]: lecture/testing/mockito.md
<!-- [BDD]: lecture/testing/bdd.md -->
<!-- [Test Converage]: lecture/testing/coverage.md -->

[Intro Threads]: lecture/threads/threads-intro.md
[Synchronisierung]: lecture/threads/threads-synchronisation.md
[Highlevel Threadkonzepte]: lecture/threads/threads-highlevel.md

:::
::: {.tab title="Praktikum"}

| Woche | Blatt  | Abgabe ILIAS und Peer-Feedback (ILIAS)                        | Vorstellung Praktikum |
|:-----:|:-------|:--------------------------------------------------------------|:----------------------|
|  16   | [B01a] | Abgabe: Do, 20.04., 08 Uhr; Peer-Feedback: Fr, 21.04., 08 Uhr | Praktikum: Fr, 21.04. |
|  17   | [B01b] | Abgabe: Do, 27.04., 08 Uhr; Peer-Feedback: Fr, 28.04., 08 Uhr | Praktikum: Fr, 28.04. |
|  18   | [B02a] | Abgabe: Do, 04.05., 08 Uhr; Peer-Feedback: Fr, 05.05., 08 Uhr | Praktikum: Fr, 05.05. |
|  19   | [B02b] | Abgabe: Do, 11.05., 08 Uhr; Peer-Feedback: Fr, 12.05., 08 Uhr | Praktikum: Fr, 12.05. |
|  20   | [B03a] | Abgabe: Do, 18.05., 08 Uhr; Peer-Feedback: Fr, 19.05., 08 Uhr | Praktikum: Fr, 19.05. |
|  21   | [B03b] | Abgabe: Do, 25.05., 08 Uhr; Peer-Feedback: Fr, 26.05., 08 Uhr | Praktikum: Fr, 26.05. |
|  22   | [B04a] | Abgabe: Do, 01.06., 08 Uhr; Peer-Feedback: Fr, 02.06., 08 Uhr | Praktikum: Fr, 02.06. |
|  23   | [B04b] | Abgabe: Do, 08.06., 08 Uhr; Peer-Feedback: Fr, 09.06., 08 Uhr | Praktikum: Fr, 09.06. |
|  24   | [B05a] | Abgabe: Do, 15.06., 08 Uhr; Peer-Feedback: Fr, 16.06., 08 Uhr | Praktikum: Fr, 16.06. |
|  25   | [B05b] | Abgabe: Do, 22.06., 08 Uhr; Peer-Feedback: Fr, 23.06., 08 Uhr | Praktikum: Fr, 23.06. |
|  26   | [B06]  | Abgabe: Fr, 30.06., 08 Uhr                                    | Praktikum: Fr, 30.06. |

[B01a]: homework/b01a.md
[B01b]: homework/b01b.md
[B02a]: homework/b02a.md
[B02b]: homework/b02b.md
[B03a]: homework/b03a.md
[B03b]: homework/b03b.md
[B04a]: homework/b04a.md
[B04b]: homework/b04b.md
[B05a]: homework/b05a.md
[B05b]: homework/b05b.md
[B06]:  homework/b06.md

:::
::::::


## Förderungen und Kooperationen

### Förderung durch DH.NRW (Digi Fellowships)

Die Überarbeitung dieser Lehrveranstaltung wurde vom Ministerium für Kultur und Wissenschaft
(MKW) in NRW im Einvernehmen mit der Digitalen Hochschule NRW (DH.NRW) gefördert:
["Fellowships für Innovationen in der digitalen Hochschulbildung"] (_Digi Fellowships_).

["Fellowships für Innovationen in der digitalen Hochschulbildung"]: https://www.dh.nrw/kooperationen/Digi-Fellows-2

### Kooperation mit dem DigikoS-Projekt

Diese Vorlesung wird zudem vom Projekt ["Digitalbaukasten für kompetenzorientiertes Selbststudium"]
(_DigikoS_) unterstützt. Ein vom DigikoS-Projekt ausgebildeter Digital Learning Scout hat
insbesondere die Koordination der digitalen Gruppenarbeiten, des Peer-Feedbacks und der
Postersessions in ILIAS technisch und inhaltlich begleitet. DigikoS wird als Verbundprojekt
von der Stiftung Innovation in der Hochschullehre gefördert.

["Digitalbaukasten für kompetenzorientiertes Selbststudium"]: https://www.digikos.de







<!-- DO NOT REMOVE - THIS IS A LAST SLIDE TO INDICATE THE LICENSE AND POSSIBLE EXCEPTIONS (IMAGES, ...). -->
::: slides
## LICENSE
![](https://licensebuttons.net/l/by-sa/4.0/88x31.png)

Unless otherwise noted, this work is licensed under CC BY-SA 4.0.
:::

