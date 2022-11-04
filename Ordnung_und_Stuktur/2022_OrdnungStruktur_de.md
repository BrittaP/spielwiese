<!--
author:   Britta Petersen, Cleo Michelsen, Semih Acis, Olaf Matthaei, Thilo Paul-Stüve, Prof. Martina Gerken, Michael Meisser, Dr. Georg Hörmann, Gregor Große-Bölting, Prof. Dr. Oliver Nakoinz

email:    b.petersen@rz.uni-kiel.de

icon: Abbildungen\Logo_cau-norm-de-lilagrey-rgb-0720_2022.png

version:  2.0

language: de

narrator: Deutsch Female

comment:  Digitale Forschungsdaten ordnen und strukturieren. Ein e-Learning Baustein zum Themenbereich Forschungsdatenmanagement, enstanden im Projekt eLBB4RDM an der CAU Kiel

tags:     Forschungsdaten, Ordnung, Struktur, dateibenennung, dateibenennungskonvention, forschungsdatenmanagement
-->

# Digitale Forschungsdaten ordnen und strukturieren

Herzlich willkommen im Lernbaustein "**Digitale Forschungsdaten ordnen und strukturieren**"!

 ![Bild](Abbildungen\TiBi_FDM_GanzerZyklus_Lila_2022-01-27_web.jpg)<!--  width="250px"
  height="250px"
  align="right"-->

Dieser Lernbaustein ist Teil einer Lernbaustein-Reihe zum Themenbereich Forschungsdatenmanagement, welche im Rahmen des durch das CAU-Programm für die digitale Lehre 2021-2023 geförderten Projektes **E-Learning Building Blocks for RDM (eLBB4RDM)** entstand.

An der Erstellung dieses Lernbausteins beteiligt war ein interdisziplinär zusammengesetztes Team aus Lehrenden, Infrastrukturmitarbeitenden und Studierenden der Christian-Albrechts-Universität zu Kiel. Die verwendeten Illustrationen wurden, wo nicht anders angegeben, von Cleo Michelsen erstellt.

Der Lernbaustein  wurde für den Einsatz in der Lehre entwickelt. Er eignet sich ebenfalls für das reine Selbststudium.

---

**Lizenzhinweis**

![Bild](Abbildungen\CC_Lizenz.png)<!--  width="50px"
-->
Dieses Werk ist mit Ausnahme verwendeten Materials von anderen Urheberrechtsinhabern unter einer [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/legalcode) lizenziert.


## Zielgruppe dieses Lernmoduls

Zielgruppe dieses Lernbausteins sind alle Menschen, die sich einen Überblick über die Ordnung und Strukturierung von digitalen Forschungsdaten verschaffen möchten. Der Lernbaustein ist für Studierende aller Fachbereiche geeignet.

Empfehlenswert ist eine Bearbeitung in der Studieneingangsphase.

## Ziele dieses Lernmoduls

![Bild](Abbildungen\2022-09-27_Zielscheibe-mit-Pfeil.jpg)<!--  width="80px"
align="right"-->

Das Lernmodul soll wichtige Aspekte näher bringen, die beim Anlegen von Ordnern und bei der Benennung von Dateien für einen strukturierten und nachvollziehbaren Umgang mit Daten zu beachten sind.

---
>**Nach Bearbeitung dieses Lernmoduls sind Sie in der Lage...**
>
>* Merkmale guter Verzeichnisstrukturen zu benennen.
>* zu beschreiben, was eine Dateibenennungskonvention ist.
>* Kriterien für gute Dateibenennungen aufzuzählen.
>* Benennungskonvention zu entwickeln und auf eigene sowie kollaborativ genutzte (Forschungsdaten-)Dateien anzuwenden.

## Hinweise zur Bearbeitung

Dieser Lernbaustein geht allgemein auf Kriterien für gute Ordnerstrukturen und Dateibenennungen ein.

Jeweils am Ende der Kapitel kann das Gelernte mit kurzen Selbsttests überprüft werden.

---

**Benötigte Software**

Für die Bearbeitung der im Lernbausteins gestellten Aufgaben benötigen Sie keine spezielle Software.

Das im Kapitel [Dokumentation von Bennungskonventionen](#Arbeitsblatt:-Dokumentation-von-dateiBenennungskonventionen) hinterlegten Arbeitsblatt liegt in verschiedenen Formaten vor, so dass es in einem Textverarbeitungsprogramm/Texteditor Ihrer Wahl bearbeitet werden kann.

---

**Bearbeitungsdauer**

Die Bearbeitungsdauer dieses Lernbausteins beträgt insgesamt etwa **15 - 20 Minuten**.

Eine intensive Auseinandersetzung mit den eingebetteten Übungsaufgaben kann die Gesamtbearbeitungszeit individuell erhöhen.

# Motivation

![Bild](Abbildungen\TiBi-Daten-ordnen_2022_web.png)<!--  width="180px"
 align="right"-->

Selbst erhobene oder nachgenutzte Forschungsdaten, die Sie in Form von Dateien abspeichern und bearbeiten, können sehr schnell unübersichtlich werden.

Zur Vermeidung wiederholter Arbeitsschritte oder gar Datenverlusten, ist ein strukturiertes Vorgehen beim Anlegen von Verzeichnis- oder Ordnerstrukturen und Dateibenennungen unbedingt zu empfehlen.

{{1}}
********************************************************************************

**Denn das hier sollte Ihnen besser nicht passieren...**

![Bild](Abbildungen\Comic_Datenverlust_v2_2022-03-08_CM_web.jpg)

 ********************************************************************************

 {{2}}
 ********************************************************************************

Vielleicht haben Sie selbst bereits die Erfahrung gemacht, dass Sie für das Finden einer bestimmten Datei viel Zeit aufwenden mussten? Oder schlimmer noch, dass Sie eine aktuelle Arbeit versehentlich überschrieben oder gelöscht haben?

Behalten Sie den Überblick und nehmen Sie sich etwas Zeit, um ein strukturiertes Vorgehen beim Anlegen von Ordnerstrukturen und der Vergabe von Dateinamen zu verfolgen. Es lohnt sich!

Neben einer Unterstützung der Übersichtlichkeit dient die Beachtung einiger Regeln bei der Dateibenennung auch der Interoperabilität Ihrer Daten.

********************************************************************************

{{3}}
********************************************************************************

Sobald Sie beginnen Ihre Daten zu bearbeiten, beispielsweise durch eine statistische Analyse, und damit Ihren Rohdatensatz zu verändern, sollten Sie zusätzlich zu Speicherorten, Ordnerstrukturen und Dateinamen auch die Kenntlichmachung des Bearbeitungsstands (**Versionierung**) Ihrer Dateien im Blick haben.

Denken Sie auch über eine **begleitende Dokumentation** nach, in der Sie Ihre eigenen Regeln und Ihr Vorgehen festhalten.

 ********************************************************************************

## Ziele einer strukturierten Datei- und Ordnerorganisation

Ein strukturiertes Vorgehen beim Anlegen und Verwalten von Ordnerstrukturen sowie bei der Vergabe von Dateinamen verfolgt folgende Ziele:

>* Einfacheres und schnelleres Suchen und Finden von Dateien
>* Vermeidung doppelter Arbeit
>* Vorbeugung von Datenverlusten durch Überschreibung oder versehentliches Löschen
>* einfache und schnelle Identifizierung des aktuellen Stands einer Datei
>* kurz-, mittel- und langfristige Nachvollziehbarkeit der Daten (damit auch nach Jahren nachvollziehbar bleibt, was, wie und weshalb getan wurde)
>* Die Zusammenarbeit mit anderen vereinfachen
>* Maschinenlesbarkeit gewährleisten

![Bild](Abbildungen\Icon_Puzzel_2022-03-23_web.jpg) <!--  width="80px"
 height="80px"
 align="right"-->

Zusammenfassend führt der strukturierte Umgang mit Ihren Dateien zu einem effizienteren und nachhaltigeren Arbeiten.
Auch für die Datenqualität und die Interoperabilität ist ein strukturiertes Vorgehen beim Anlegen von Ordnerstrukturen und Dateibenennungen ein wichtiges Puzzleteil.

### Selbsttest - Motivation

![](Abbildungen\Icon_FrageTyp_2022_web.jpg)<!--  width="80px"
   align="right"-->

**Welche der folgenden Ziele werden u. a. mit einem strukturierten Anlegen von Ordnern sowie der strukturierten Vergabe von Dateinamen verfolgt?** (Mehrfachauswahl möglich)

[[X]] Datenverlust vermeiden
[[X]] Doppelte Bearbeitung vermeiden
[[ ]] Einhaltung von Richtlinien der Universität
[[ ]] Vorgaben der Deutschen Forschungsgemeinschaft (DFG) erfüllen
[[X]] Zusammenarbeit vereinfachen

---

![](Abbildungen\Icon_FrageTyp_2022_web.jpg)<!--  width="80px"
   align="right"-->

**Was sollte man ~~neben~~ einer logischen Ordnerstruktur und strukturierten Dateibenennungen im Hinblick auf eine gute Dateiorganisation noch im Blick haben?** (Mehrfachauswahl möglich)

[[ ]] Analysemethoden
[[ ]] Auswahl des für die Aufgabe geeigneten Programms
[[X]] Datei-Versionierung
[[X]] Dokumentation des eigenen Vorgehens

---


# Pfade und Pfadnamen

Jede Datei, an der Sie arbeiten, braucht einen eindeutigen und individuellen Pfadnamen innerhalb des Dateisystems.

>**Je nach genutztem Betriebssystem besteht ein Pfadname aus den Elementen:**
>
>* Laufwerks- oder Datenträgerbezeichnung
>* Liste von Ordnern bzw. (Unter-)Ordnern
>* Dateinamen

Pfade führen zu Ordnern und Dateien. Sie sind sozusagen die genauen Adressen der Dateien und Ordner innerhalb eines bestimmten Systems.

Moderne Betriebssysteme sind in der Lage Daten (Dateien und Ordner) auf mehreren physikalischen Datenträgern zu verwalten,  d. h. Daten können auf verschiedenen Datenträgern, wie z. B. Festplatten, USB-Sticks, SD-Karten usw. gespeichert und von dort aus abrufbar sein.  

## Pfade unter Windows und Unix
Bei Vergabe von Pfadnamen gehen die beiden Betriebssysteme Windows und Unix unterschiedliche Wege:

>**Windows** stellt einem Pfad stets einen Buchstaben voraus. Dieser Buchstabe steht für den entsprechenden Datenträger bzw. das entsprechende Laufwerk, in dem sich der Datenträger befindet.
>
> Als Trennzeichen nutzt Windows den umgekehrten Schrägstrich (\) in Pfaden.
>
>Die Pfadlänge beschränkt Windows auf maximal 256 Zeichen.
>
>**Ein vollständiger Pfadname sieht unter Windows beispielsweise so aus: **
>
>![](Abbildungen\Abb_Pfadbeispiel_2022_bp.png "Hier steht **C:\\** für das Laufwerk/den Datenträger, auf dem die Datei abgelegt ist. Auf diesem Laufwerk C liegt ein Ordner **uni**, in welchem sich ein Ordner **physik_I** befindet. Innerhalb des Ordners physik_I befindet sich ein Ordner **protokolle**, in welchem eine Datei mit dem Namen **beispielprotokoll.docx** abgelegt ist.")<!--  width="350px" align="middle"-->

>**Unix** und **Unix-Derivate** (z. B. Linux) arbeiten mit einem sogenannten „Wurzelverzeichnis“ (root directory). Von diesem Wurzelverzeichnis aus wird rein verzeichnisorientiert, ohne Angabe eines Laufwerkes/Datenträgers adressiert. Aus einer Unix-Pfadangabe alleine ist daher nicht ersichtlich, auf welchem physikalischen Datenträger eine bestimmte Datei liegt. In der Regel liegt das Wurzelverzeichnis auf dem Datenträger, von welchem der Systemstart erfolgt. Weitere Datenträger werden durch die Verwaltung von sogenannten Einhängepunkten (mount points) eingebunden.
>
>Als Trennzeichen nutzt Unix den Schrägstrich (/) in Pfaden.
>
>**Ein vollständiger Pfadname sieht unter einem UNIX-System beispielsweise so aus: **
>
>![](Abbildungen\Abb_Pfadbeispiel_Unix2022_bp.png "Hier liegt ein Ordner **uni** im Wurzelverzeichnis, in welchem sich ein Ordner **physik_I** befindet. Innerhalb des Ordners physik_I befindet sich ein Ordner **protokolle**, in welchem eine Datei mit dem Namen **beispielprotokoll.docx** abgelegt ist. Es ist nicht ersichtlich, auf welchem physikalischen Datenträger die Datei **beispielprotokoll.docx** gespeichert ist.")<!--  width="350px" align="middle"-->

### Selbsttest - Pfade

![](Abbildungen\Icon_FrageTyp_2022_web.jpg)<!--  width="80px"
   align="right"-->


**Welches der folgenden Elemente ist NICHT Bestandteil eines Pfadnamens?** (Mehrfachauswahl möglich)

[[ ]] Dateiname
[[X]] Datum
[[ ]] Liste von Ordnern bzw. (Unter-)Ordnern
[[ ]] Laufwerks- oder Datenträgerbezeichnung
---

![](Abbildungen\Icon_FrageTyp_2022_web.jpg)<!--  width="80px"
   align="right"-->


**Welche der folgenden Merkmale gelten für Pfade unter einem Windows-System?** (Mehrfachauswahl möglich)

[[ ]] Als Trennzeichen wird der Schrägstrich (/) verwendet.
[[x]] Die maximale Pfadlänge erlaubt 256 Zeichen
[[X]] Ein Pfad besteht aus den Elementen "Laufwerks- oder Datenträgerbezeichnung", "Liste von Ordnern bzw. Unterordnern" und "Dateinamen".
[[ ]] Von einem Wurzelverzeichnis aus wird rein verzeichnisorientiert adressiert.



# Ordner benennen und strukturieren
Unabhängig davon, an welchem Speicherort oder -medium Sie Ihre Dateien ablegen: Sie sollten sich ein System für Ihre Daten einrichten, welches Ihnen einen möglichst **einfachen und schnellen Zugriff** auf Ihre Dateien ermöglicht, **Doppelarbeit vermeidet** und sicherstellt, dass Ihre **Daten adäquat gesichert** werden.

>Die Entwicklung einer **logischen Ordnerstruktur** ist hierfür ein sehr guter Startpunkt!

---

**Verschiedene Wege können zum Ziel führen!**

 ![](Abbildungen\Icon_Ordner_2022_web.jpg)<!--  width="80px"
   align="right"--> Für die Erstellung einer Ordnerstruktur gibt es kein "Patentrezept", welches gleichermaßen für jeden Menschen und jedes Projekt funktionieren würde. Es gibt viele Möglichkeiten, Dateien zu organisieren und Ordnerstrukturen anzulegen.

Nehmen Sie sich daher etwas Zeit und überlegen Sie, welche Vorgehensweise für Sie und für Ihre Studienprojekte sinnvoll und passend ist.

## Richtlinien für die Entwicklung einer Ordnerstruktur

Versuchen Sie bei der Entwicklung einer logisch aufgebauten Ordnerstruktur folgende Punkte zu beachten:

>![](Abbildungen\Icon_Glühbirne_2022-02-23_web.jpg)<!--  width="80px" align="right"-->
>
> * **Ordner fassen Dateien mit gemeinsamen Eigenschaften zusammen**
> * **Aussagekräftige Ordnernamen verweisen auf die Inhalte**
> * **Ordner hierarchisch strukturieren**
> * **Nicht zu viele Unterordner anlegen**
> * **Laufende und abgeschlossene Arbeiten trennen**
> * **Rohdaten immer gesondert ablegen**
> * **Backup nicht vergessen**
> * **Nicht mehr benötigte Dateien regelmäßig löschen**
> * **Gegebenenfalls eine Zwischenablage anlegen**
> * **Ausprobieren und anpassen**
> * **Für gemeinsam genutzte Dateien gemeinsame Regeln festlegen**
> * **Konsequent bleiben**

{{1}}
********************************************************************************

**Ordner fassen Dateien mit gemeinsamen Eigenschaften zusammen**

![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Legen Sie Ordner an, die Dateien mit gemeinsamen Eigenschaften gruppieren, so dass sich Informationen zu einem bestimmten Thema an einem Ort befinden.

Denken Sie bei der Gruppierung darüber nach, wie Sie Ihre Dateien in Zukunft durchsuchen möchten!

Mögliche Kategorien für Ihre Ordner wären beispielsweise Ihre Studienfächer, die zugehörigen Veranstaltungsformen (Vorlesungen, Seminare, Übungen, Praktika) und/oder die Semester, in denen Sie an den Veranstaltungen teilgenommen haben.

Digitale Forschungsdaten, die Sie etwa im Rahmen eines Praktikums oder einer Übung erheben und bearbeiten, können Sie beispielsweise nach Teilnehmergruppe, Datenerhebungsmethode, Datum bzw. Zeitraum oder auch nach Art der Dateien (Formate) ordnen.

********************************************************************************

{{2}}
********************************************************************************

**Aussagekräftige Ordnernamen verweisen auf die Inhalte**

![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Stellen Sie sicher, dass Sie klare und angemessene Ordnernamen verwenden, die den Inhalt des Ordners prägnant wiedergeben.

Sie haben sich eben überlegt, nach welchen Merkmalen Sie Ihre Dateien gruppieren möchten. Formulieren Sie im nächsten Schritt auf diese Merkmale verweisende Ordnernamen.

********************************************************************************

{{3}}
********************************************************************************

**Ordner hierarchisch strukturieren**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Entwerfen Sie eine hierarchisch organisierte Ordnerstruktur. Beginnen Sie mit einer begrenzten Anzahl von Ordnern für die übergeordneten Themen und legen Sie dann innerhalb dieser Ordner weitere spezifischere Ordner an.

Folgendes Beispiel stellt eine hierachische Strukturierung dar:

1. Projekt
2. Arbeitsgruppe
3. Experiment
4. Parameter

-> Innerhalb eines bestimmten Projekts kann es mehrere Arbeitsgruppen geben. Jede Arbeitsgruppe führt eigene Experimente durch, in denen verschiedene Parameter betrachtet werden.

********************************************************************************

{{4}}
********************************************************************************

**Nicht zu viele Unterordner anlegen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Versuchen Sie ein Ablagekonzept zu entwickeln, das nicht zu komplex aufgebaut ist.

Halten Sie die Anzahl der Unterordner überschaubar - wenn Sie zu viele Unterordner haben, kann das dies die Navigation erschweren. Andererseits wollen sie auch nicht zahlreiche Dateien innerhalb eines Ordners durchsuchen müssen, um die gewünschte Datei zu finden.

Finden Sie eine für Sie und Ihre Projekte stimmige Balance!

********************************************************************************

{{5}}
********************************************************************************

**Laufende und abgeschlossene Arbeiten trennen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Es kann sehr hilfreich sein, Entwürfe und abgeschlossene Arbeiten in getrennten Ordnern abzulegen.

Verschieben Sie die Dateien, an denen Sie nicht mehr arbeiten, regelmäßig in einen anderen Ordner oder an einen anderen Ort, z. B. in einen speziellen Archivordner oder auf ein anderes Speichermedium, beispielsweise eine externe Festplatte.

Auf diese Weise können Sie leichter überprüfen und im Auge behalten, was Sie behalten müssen, während Sie weiterarbeiten.

********************************************************************************

{{6}}
********************************************************************************

**Rohdaten immer gesondert ablegen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Ihre Rohdaten sollten Sie stets getrennt von den Daten aufbewahren, an denen Sie arbeiten.

Speichern Sie grundsätzlich immer eine separate "Rohdaten"-Datei, die unverändert bleibt, so dass Sie immer eine Kopie der unveränderten Originaldaten haben! Es ist möglich, dass Sie darauf zurückgreifen müssen.

Um ein versehentliches Bearbeiten zu verhindern, können Sie sich selbst die Schreibrechte für die Rohdaten-Dateien entziehen.
Das macht es auch schwieriger, in einem Moment der Schwäche schnell mal manuelle Änderungen vornehmen zu wollen.

********************************************************************************

{{7}}
********************************************************************************

**Backup nicht vergessen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Stellen Sie sicher, dass Ihre Dateien, egal ob sie sich auf Ihrem lokalen Laufwerk oder einem Netzlaufwerk befinden, regelmäßig gesichert werden.

********************************************************************************

{{8}}
********************************************************************************

**Nicht mehr benötigte Dateien löschen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Überprüfung Sie regelmäßig zu bestimmten Zeitpunkten oder jeweils am Ende einer abgeschlossenen Arbeit Ihre Dateien und löschen Sie die nicht mehr benötigten Dateien.

Durch das Löschen überflüssiger Dateien wird neuer Speicherplatz für ihre neuen Daten frei und lässt das Licht auf die relevanten Daten fallen.

Tragen Sie sich ggf. eine Erinnerung in Ihren Kalender ein, damit Sie es nicht vergessen!

********************************************************************************

{{9}}
********************************************************************************

**Gegebenenfalls eine Zwischenablage anlegen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Für Dokumente, die Sie (noch) nicht klar einem Ihrer Verzeichnisse zuordnen können, kann ein Ordner „Temp“ oder „Noch einzuordnen“ angelegt werden. Eine solche Zwischenablage sollte aber unbedingt regelmäßig aufgeräumt werden.

********************************************************************************

{{10}}
********************************************************************************

**Ausprobieren und anpassen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Versuchen Sie unter Berücksichtigung der hier genannten Hinweise eine Ordnerstruktur zu entwickeln, deren Ordnung Ihren persönlichen Bedürfnissen entspricht.

Es ist ggf. sinnvoll, das Konzept anhand einiger Beispielfälle auszuprobieren. Erst dann – ggf. nach entsprechenden Änderungen – sollten Sie mit einer Umsetzung in größerem Stil beginnen. So vermeiden Sie, zu einem späteren Zeitpunkt Ihre Ordnerstruktur eventuell komplett umbauen zu müssen.

Überprüfen Sie regelmäßig, ob Ihre Ablagestruktur noch zu Ihren Anforderungen passt. Ein Hinweis auf Änderungsbedarf könnte die Anzahl der Dateien sein, die Sie nicht eindeutig zuordnen können und die aus diesem Grunde in einer Zwischenablage landen.

Halten Sie eventuelle Änderungen Ihrer Strukturen in einer [Dokumentation](#dokumentation-von-benennungskonventionen) fest.

********************************************************************************

{{11}}
********************************************************************************

**Für gemeinsam genutzte Dateien gemeinsame Regeln festlegen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Wenn Sie Ihre Daten und Dateien gemeinsam mit Kommiliton*innen nutzen, sollten Sie gemeinsam Regeln zum Umgang mit den Daten festlegen.

Entwickeln Sie eine gemeinsame Ordnerstruktur, eine gemeinsame Dateibenennungskonvention und legen Sie Zugriffsrechte fest.

Dokumentieren Sie Ihre gemeinsamen Regeln!

********************************************************************************

{{12}}
********************************************************************************

**Konsequent bleiben**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Seien Sie konsequent - wenn Sie ein Ordnungs- und Benennungsschema für Ihre Dateiablage entwickeln, ist es wichtig, dass Sie sich an eine einmal festgelegte Methode halten.

Versuchen Sie nach Möglichkeit, sich möglichst früh ein Ordnungsschema zu überlegen. Dokumentieren Sie Ihr Ordnungs- und Benennungsschema!

Halten Sie eventuelle Anpassungen in einer Dokumentation fest.

********************************************************************************

## Beispiele für mögliche Ordnerstrukturen

Folgende Beispiele sollen Ihnen als Orientierungshilfe für die Erstellung eigener Ordnerstrukturen dienen:

---

![](Abbildungen\Abb_OrdnerstrukturUebungXY_2022_bp.png "Beispielhafte Orderstruktur für eine Übung, in welcher Daten erhoben, ausgewertet und in einer Hausarbeit und/oder einem Poster zusammengefasst und beschrieben werden.  (Abbildung: Britta Petersen)")<!--  width="250px" align="center"-->

---

![](Abbildungen\Abb_OrdnerstrukturArchproject_2022_bp.png "Beispielhafte Orderstruktur für ein wissenschaftliches Projekt aus dem Fachbereich Ur- und Frühgeschichte. (Abbildung: Britta Petersen nach Angaben von Oliver Nakoinz)")<!--  width="250px" align="center"-->

### Selbsttest - Ordner

![](Abbildungen\Icon_FrageTyp_2022_web.jpg)<!--  width="80px"
   align="right"-->

**Ordnen Sie die folgenden Begriffe in eine nachvollziehbare hierarchische Struktur! Ordnen Sie dabei vom Unspezifischen (1. Ebene) zum Spezifischen (4. Ebene).**

- [[Daten]  [Rohdaten] [Praktikum] [Studienfach]]
- [    [ ]       [ ]     [ ]     [x]     ]  1. Ebene
- [    [ ]       [ ]     [x]     [ ]     ]  2. Ebene
- [    [x]       [ ]     [ ]     [ ]     ]  3. Ebene
- [    [ ]       [x]     [ ]     [ ]     ]  4. Ebene
***********************************************************************

Vom Unspezifischen zum Spezifischen sortiert ergibt sich folgende Ordnung:

Ebene 1: Studienfach

Ebene 2: Praktikum

Ebene 3: Daten

Ebene 4: Rohdaten

Im Rahmen eines Studienfaches gibt es verschiedene Praktika, in denen Daten anfallen und analysiert werden, die jeweils eigene Datengrundlagen (Rohdaten) haben.

***********************************************************************
---

![](Abbildungen\Icon_FrageTyp_2022_web.jpg)<!--  width="80px"
   align="right"-->

**Ordner sollten hierarchisch strukturiert werden. Warum sollten jedoch nicht übermäßig viele Unterordner angelegt werden?**

[[ ]] Viele Unterordner erhöhen den Verbrauch an Speicherplatz
[[X]] Viele Unterordner erschweren die Navigation zu den Dateien
[[X]] Viele Unterordner führen zu langen Pfadnamen, was zu einer Überschreitung der von Windows maximal zugelassenen Pfadlänge führen kann.

---

![](Abbildungen\Icon_FrageTyp_2022_web.jpg)<!--  width="80px"
   align="right"-->

**Was sollten Sie grundsätzlich immer mit Ihren Rohdaten machen?**

[[ ]] Nichts, Rohdaten müssen nicht gespeichert werden.
[[X]] Rohdaten sollten stets in einer unveränderten Version gespeichert sein.
[[ ]] Rohdaten sollten vor der Bearbeitung in unterschiedliche Formate umgewandelt werden.

# Dateien strukturiert benennen
Wenn wir um 3:00 Uhr nachts verzweifelt nach der wirklich aktuellen Version der Hausarbeit suchen, die wir spätestens morgen früh um 9:00 Uhr abgeben müssen, können uns wild vergebene Dateinamen um den Verstand bringen!

{{1}}
********************************************************************************
**Welche dieser Dateien ist denn jetzt die aktuelle...?**

![Bild](Abbildungen\Comic_Dateibenennung_v2_2022-04-14_CM_web.jpg)

********************************************************************************

{{2}}
********************************************************************************

Unspezifische und unstrukturierte Dateibenennung kann viel Zeit kosten.

Nicht nur durch ein erschwertes Auffinden der tatsächlich aktuellsten Version einer Datei, sondern im schlimmsten Fall durch das versehentliche Überschreiben einer aktuellen Version, die umfangreiche Änderungen enthielt, mit einer älteren.  

********************************************************************************

## Richtlinien für die Entwicklung einer Dateibenennungskonvention

Ein Regelwerk für die Benennung von Dateien wird als **Dateibenennungskonvention** bezeichnet und genau wie Ihr Regelwerk zum Anlegen und Benennen von Ordnern sollte auch Ihr Regelwerk für die Benennung von Dateien dokumentiert und möglichst konsequent angewendet werden.

**Beachten Sie die folgende Punkte beim Benennen Ihrer Dateien:**

> ![](Abbildungen\Icon_Glühbirne_2022-02-23_web.jpg)<!--  width="80px" align="right"-->
>
> * **Konventionen frühzeitig festlegen**
> * **Unterschiedliche Konventionen für verschiedene Dateitypen sind erlaubt**
> * **Prüfen, ob bereits etablierte Konventionen existieren**
> * **Weniger als 32 Zeichen (besser noch weniger) für Dateinamen benutzen**
> * **Dateinamen sollten deutlich auf den Inhalt der Datei hinweisen**
> * **Grundsätzlich keine unspezifischen Dateinamen verwenden**
> * **Keine Sonderzeichen, Umlaute oder Leerzeichen in Dateinamen benutzen**
> * **Erlaubte Sonderzeichen sind Unterstrich ( _ ) und Bindestrich ( - )**
> * **Führende Null(en) bei Nummerierungen verwenden**
> * **Datumsangaben nach der ISO 8601**

{{1}}
********************************************************************************

**Konventionen frühzeitig festlegen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Es ist wichtig, frühzeitig eine Dateibenennungskonvention zu erstellen.

Machen Sie sich bereits Gedanken, bevor Sie mit dem Sammeln von Dateien oder Daten beginnen.  

Sie vermeiden einen Rückstau von unorganisierten Inhalten, der zu verlegten oder verlorenen Daten führen kann!

Dies gilt insbesondere für kollaborativ genutzte Dateien.

********************************************************************************

{{2}}
********************************************************************************

**Unterschiedliche Konventionen für verschiedene Dateitypen sind erlaubt**

![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Bestimmen Sie, für welche Dateigruppe Ihre Namenskonvention gelten soll.

Sie können unterschiedliche Konventionen für verschiedene Dateigruppen verwenden.

Dokumentieren Sie Ihre Konventionen entsprechend, beispielsweise: Diese Konvention wird für alle meine Mikroskopiedateien gelten, vom Rohbild bis zum bearbeiteten Bild.

********************************************************************************

{{3}}
********************************************************************************

**Prüfen, ob bereits etablierte Konventionen existieren**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Prüfen Sie, ob es in Ihrem Fachgebiet oder Ihrer Gruppe bereits etablierte Konventionen für die Benennung von Dateien gibt.

Falls ja, orientieren Sie sich an den etablierten Konventionen.

********************************************************************************

{{4}}
********************************************************************************

**Weniger als 32 Zeichen (besser noch weniger) für Dateinamen benutzen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Lange Dateinamen (und zu viele Unterordner) sollten vermieden werden. Sie vermeiden damit, die zulässige Pfadlänge Ihres Betriebssystems zu überschreiten (Windows erlaubt maximal 256 Zeichen).

********************************************************************************

{{5}}
********************************************************************************

**Dateinamen sollten deutlich auf den Inhalt der Datei hinweisen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Ihr Dateiname sollte den Inhalt der Datei möglichst gut beschreiben, gleichzeitig aber nicht zu lang sein.

Entwerfen Sie ein System von Abkürzungen (z. B. HA für Hausarbeit) und dokumentieren Sie Ihre Abkürzungen in einer README-Datei.

Wenden Sie Ihre gewählten Abkürzungen stets konsequent an.

********************************************************************************

{{6}}
********************************************************************************

**Grundsätzlich keine unspezifischen Dateinamen verwenden**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Dateinamen wie etwa "HausarbeitNeu" oder "HausarbeitFinal" sind sehr unspezifisch und angehängte Zusätze wie "Neu" oder "Final" sehr schnell nicht mehr aktuell.

Vermeiden Sie unspezifische Bezeichnungen sowohl in Bezug auf den Inhalt der Datei als auch in Bezug auf den Bearbeitungsstand.

Nutzen Sie stattdessen spezifischere Bezeichnungen für den Inhalt und Versionsbezeichnungen für den Bearbeitungsstand (z. B. HA-SeminarXYZ-v01.docx)

********************************************************************************

{{7}}
********************************************************************************

**Keine Sonderzeichen, Umlaute oder Leerzeichen in Dateinamen benutzen**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Die Nutzung von Umlauten und Leerzeichen in Dateinamen sind zwar erlaubt, aber nicht empfohlen, da nicht alle Systeme mit diesen Zeichen umgehen können, wodurch Fehler auftreten können.

Auf Sonderzeichen, wie etwa \*, \~, \#, \{, \}, \[, \], \|, \`, \$, \@, \\ usw. sollten Sie generell verzichten, da diese Zeichen Funktionen in Betriebssystemen oder Programmen haben können.

********************************************************************************

{{8}}
********************************************************************************

**Bessere Lesbarkeit: Erlaubte Sonderzeichen Unterstrich (\_) und Bindestrich (-)**

![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Für eine bessere Lesbarkeit können Sie die Zeichen Unterstrich (_) und Bindestrich (-) verwenden.

Auch Groß- und Kleinschreibung kann im Sinne einer besseren Lesbarkeit verwendet werden.

**Beispiel**:

Inhalt\_der\_Datei\_v01.docx oder

Inhalt-der-Datei-2022-01-15-v01.docx oder

InhaltDerDateiV01.docx

********************************************************************************

{{9}}
********************************************************************************

**Führende Null(en) bei Nummerierungen verwenden**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Wenn Sie sequentielle Nummern verwendet möchten, so sollten stets führende Nullen verwendet werden:

* für 1-10 -> 01-10;
* für 1-100 -> 001-100
* für 1-1000 -> 0001-1000

Eine Sortierung nach Nummerierung ist etwa bei den Dateien sinnvoll, die sich z. B. durch die Proben-ID unterscheiden, ansonsten aber Dokumente zu einem immer wiederkehrenden Thema sind.

Die führende Null bei Nummerierungen ist für eine korrekte fortlaufende Nummerierung nötig. Ohne führende Nullen sortiert Ihr Computer folgendermaßen: 1, 10, 11, 12, 2, 20, 201, 21, 3, …

********************************************************************************

{{10}}
********************************************************************************

**Datumsangaben nach der ISO 8601**
![](Abbildungen\Icon_Tipp2_2022-02-24_cm_web.jpg)<!--  width="80px" align="right"-->

Eine chronologische Sortierung ist bei den Dateien absolut sinnvoll, die sich z. B. durch das Erstelldatum unterscheiden, ansonsten aber Dokumente, Tabellen oder Präsentationen zu einem immer wiederkehrenden Thema sind.

Datumsangaben sollten dabei stets der ISO 8601 folgen (YYYY-MM-DD oder YYYYMMDD). Die ISO 8601 ist eine international geltende Konvention für die Datumsangabe. Die Nutzung der Norm stellt sicher, dass Datumsangaben richtig gelesen und verstanden werden.

Eine Datumsangabe im Format YY-MM-DD oder DD-MM-YY sollten Sie unbedingt vermeiden, denn diese Form kann zu Fehlinterpretationen führen: Die Datumsangabe 22-04-12 kann sowohl als 22.04.2012 als auch als 12.04.2022 interpretiert werden!    

********************************************************************************

## Beispiele für Benennungskonventionen und Dateinamen

| Beispiele für Benennungskonventionen        | Beispiel-Dateiname |
|:--------------------------  |:--------------      |
| [Inhaltsbeschreibung]\_[ErstelldatumISO8601]\_[Experiment]\_[Bearbeiter\*in]\_[Version].Dateiendung  | Protokoll\_2020-01-05\_O2-Messung\_YA\_v1.odt           |
| [LfdNummer]\_[Erhebungsort]\_[Parameter]\_[Bearbeiter\*in]_[ErhebungsdatumISO8601].Dateiendung    | 07\_Barkau\_N2\_Nina_20040503.csv           |
| [Erhebungsjahr]\_[Inhalt-Ort]\_[Bearbeitungsstand]\_[Bearbeiter\*in].Dateiendung | 2019\_KartierungSchaber-Ploen\_original_TF.tif          |
|   [YYYYMMDD]\_[Projekt]\_[Ort]\_[Event].Dateiendung    | 20130622\_Pirovac\_Orvieto\_KickOffMeeting.Dateiendung  |
| [Institutskennung]\_[Sammlungskennung]\_[Merkmal]\_[Inventarnummer]\_[Aufnahmekennung]\_[Typenkennung].Dateiendung | sgs\_mup\_creed\_a-123-dmg-12-54\_uv1\_m.tif |




### Selbsttest - Dateibenennungen

![](Abbildungen\Icon_FrageTyp_2022_web.jpg)<!--  width="80px"
   align="right"-->


**Wie dürfen Elemente eines Dateinamens im Sinne einer besseren Lesbarkeit getrennt werden?** (Mehrfachauswahl möglich)

[[ ]] Trennung mittels Leerzeichen
[[x]] Trennung mittels Unterstrichen
[[X]] Trennung mittels Groß- und Kleinschreibung
[[ ]] Trennung mittels Punkten
[[x]] Trennung mittels Bindestrichen

---

![](Abbildungen\Icon_FrageTyp_2022_web.jpg)<!--  width="80px"
   align="right"-->


**Welche dieser Beispiele folgen einer guten Benennungskonvention?** (Mehrfachauswahl möglich)

[[X]] 002-ParameterX-2019-10-19.xlsx
[[ ]] 200319-InterviewMA.docx
[[X]] 2022-01-02_Sequenz001-Exp001.csv
[[ ]] HausarbeitFertig.docx
[[ ]] slkfjsifheid78e99.mp3
***********************************************************************

Die Dateinamen **slkfjsifheid78e99.mp3** und **HausarbeitFertig.docx** weisen nicht ausreichend gut auf den Inhalt der Datei hin bzw. nutzen unspezifische Bezeichnungen.

Der Dateiname **200319-InterviewMA.docx** nutzt eine Datumsangabe, die nicht der ISO 8601 entspricht, wodurch unklar ist, ob sich die Datumsangabe auf den 20.03.2019 oder auf den 19.03.2020 bezieht.

Die Dateinamen **002-ParameterX-2019-10-19.xlsx** und **2022-01-02_Sequenz001-Exp001.csv** nutzen eine Datumsangabe nach ISO 8601, sie weisen spezifisch auf den Inhalt hin, ermöglichen eine automatische Sortierung nach Datum bzw. Nummerierung und Nutzen korrekte Trennzeichen zur besseren Lesbarkeit.

***********************************************************************

# Dokumentation

Mit Hilfe einer geeigneten Dokumentation können Sie für sich selbst und für andere festhalten, welchen Regeln Ihre Ordnerstruktur und Ihre Dateibenennungen folgen, sodass Sie und andere kurz-, mittel- und langfristig Ihre eigenen Strukturen nachvollziehen können.

Eine Dokumentation von Ordnerstrukturen und Namenskonventionen erfolgt gemeinhin in einer sogenannten **README-Datei**.

**README-Dateien** sollten stets zusammen mit den Dateien abgelegt werden, für die die jeweilige Dokumentation gelten soll. Ein guter Speicherort ist die jeweils oberste Ordnerebene (vgl. [Beispiele für mögliche Ordnerstrukturen](#25)).

**README-Dateien** sollten stets in einem Format angelegt werden, das einfach und schnell lesbar ist. Eine reine Textdatei ist für eine Dokumentation vollkommen ausreichend. Empfehlenswerte Formate für Ihre README-Dateien sind beispielsweise reine Textdateien (.txt), Markdown-Dateien (.md) oder Rich-Text-Dateien (.rtf). Diese Formate sind interoperabel und benötigen kein spezielles Programm, sondern können von jedem beliebigen Texteditor geöffnet werden.

Informationen in den Dateinamen und Ordnerbezeichnungen, die Sie über Abkürzungen kodieren, sollten Sie unbedingt in übersichtlicher Form in Ihrer Dokumentation festhalten.

### Arbeitsblatt: Dokumentation von Dateibenennungskonventionen

Bearbeiten Sie das Arbeitsblatt "Dokumentation von Dateibenennungskonventionen" in einem von Ihnen bevorzugten Format.

Das vollständige bearbeitete Arbeitsblatt eignet sich bereits als Dokumentation für Ihre Benennungskonventionen und kann als README gemeinsam mit den zugehörigen Dateien abgespeichert werden!

>Bitte nutzen Sie die **rechte Maustaste** und wählen **"Link speichern unter"** um das Arbeitsblatt "Dokumentation von Dateibenennungskonventionen" im txt-Format herunterzuladen: <A HREF="Download-Dateien\AB_DokuDateibenennung-v1_2022.txt" download>2022\_AB\_DokuDateibenennung.txt</A>

>Bitte nutzen Sie die **rechte Maustaste** und wählen **"Link speichern unter"** um das Arbeitsblatt "Dokumentation von Dateibenennungskonventionen" im rtf-Format herunterzuladen: <A HREF="Download-Dateien\AB_DokuDateibenennung-v1_2022.rtf" download>2022\_AB\_DokuDateibenennung.rtf</A>

>Bitte nutzen Sie die **rechte Maustaste** und wählen **"Link speichern unter"** um das Arbeitsblatt "Dokumentation von Dateibenennungskonventionen" im md-Format: <A HREF="Download-Dateien\AB_DokuDateibenennung-v1_2022.md" download>2022\_AB\_DokuDateibenennung.md</A>

# Umbenennungstools
Es kann vorkommen, dass Sie mehrere Dateien gleichzeitig umbenennen möchten.

Dies kann z. B. der Fall sein, wenn ...  

* automatisch generierte Dateinamen, etwa von Digitalkameras oder Analysegeräten in Laboren, einheitlich nach einem bestimmten Schema umbenannt werden sollen oder
* bestimmte Zeichen, wie z. B. Sonderzeichen oder Leerzeichen, aus einer Reihe von Dateinamen entfernt werden oder ersetzt werden sollen.

Für diese Fälle existieren Software-Tools, die es Ihnen ermöglichen, mehrere Dateien gleichzeitig in einem Schritt umzubenennen.


Je nach Betriebssystem können beispielsweise folgende Tools zur gleichzeitigen automatischen Umbenennung genutzt werden:

**Windows**:

* Ant Renamer (https://www.antp.be/software/renamer)
* RenameIT (https://sourceforge.net/prpjects/renameit)
* Bulk Rename Utility (https://www.bulkrenameutility.co.uk/)
* Total Commander (https://www.ghisler.com/deutsch.htm)

**Mac**:

* Renamer 5 (for Mac) (https://renamer.com/)
* Name Changer (https://mrrsoftware.com/namechanger/)
* ExifRenamern (https://exifrenamer.en.softonic.com/mac)

**Linux**:

* GNOME Commander (https://www.nongnu.org/gcmd/)
* GPRename (http://gprename.sourceforge.net/)

**Unix**:

* rename command 


# Kurz zusammengefasst

>**~~Motivation~~**
>
>Eine besondere Herausforderung im Umgang mit digitalen Forschungsdaten ist die schiere Menge der verfügbaren Daten. Ein strukturiertes Vorgehen beim Abspeichern und Benennen von Dateien hilft dabei, den **Überblick** zu **behalten** und führt zu einem **effizienteren und nachhaltigeren Arbeiten**. Auch für die **Datenqualität** und die **Interoperabilität** ist ein strukturiertes Vorgehen beim Anlegen von Ordnerstrukturen und Dateibenennungen ein wichtiger Baustein.

>**~~Pfade und Pfadnamen~~**
>
>Jede Datei, hat einen eindeutigen und individuellen Pfadnamen innerhalb eines Dateisystems. Pfade sind die **genauen Adressen** der Dateien und Ordner innerhalb eines bestimmten Systems. Je nach genutztem Betriebssystem besteht ein Pfadname aus den Elementen: **Laufwerks- oder Datenträgerbezeichnung**, einer **Liste von Ordnern bzw. (Unter-)Ordnern** und dem **Dateinamen**. Erlaubte **Pfadlängen** (Anzahl Zeichen innerhalb eines Pfades) können begrenzt sein.

>**~~Ordnerstrukturen~~**
>
>Es gilt eine für sich selbst und das jeweilige Projekt passende Ordnerstruktur zu entwickeln. Generell sollten Ordner **Dateien mit gemeinsamen Eigenschaften zusammenfassen**. Gute Ordnernamen weisen auf diese gemeinsamen Eigenschaften hin. Zu empfehlen ist eine **hierarchische Struktur**, in der vom Übergeordneten zum Speziellen sortiert wird. Dabei sollten **nicht zu viele Unterordner** angelegt werden. **Rohdaten** sollten stets **gesondert und unverändert** abgespeichert werden. **Regelmäßiges Löschen** nicht mehr benötigter Dateien sowie eine **Trennung laufender und abgeschlossener Arbeiten** unterstützt die Aufrechterhaltung von Übersichtlichkeit. Regelmäßiges **Backup** der Daten sowie eine **Dokumentation** des eigenen Vorgehens sollten nicht vergessen werden.

>**~~Dateibenennungskonventionen~~**
>
>Dateien mit einer Namenskonvention bieten eine **Vorschau auf den Inhalt**, können **logisch geordnet** werden (z. B. nach Datum jjjj-mm-tt oder Probenart), geben **Hinweise auf** die verantwortlichen **Ersteller\*innen** und **Bearbeiter\*innen** sowie über den **Verlauf von Änderungen** (Versionen) an den Dateien. Dateinamen sollten stets so **kurz wie möglich** sein und unter einer Länge von 32 Zeichen bleiben. Unspezifische

>**~~Dokumentation~~**
>
>Eine Dokumentation der eigenen Regeln für Ordnerstrukturen und Dateibenennungskonventionen stellt sicher, dass Sie und andere kurz-, mittel- und langfristig Ihre **eigenen Strukturen und Vorgehensweisen nachvollziehen** können. Gemeinhin erfolgt eine Dokumentation von Ordnerstrukturen und Namenskonventionen in einer **README-Datei**, welche gemeinsam mit den Ordnern und Dateien abgelegt wird, für die die Dokumentation gelten soll. Eine dokumentierende **README-Datei** sollte in einem **möglichst einfachen Format** gespeichert werden und neben den **Regeln** zur **Strukturierung von Ordnern** und zur **Benennung von Dateien** auch Informationen zu ggf. genutzten **Abkürzungen und Akronymen** enthalten.

# Feedback

Wir freuen uns sehr über Feedback zu diesem Lernbaustein und möchten Sie daher bitten, den folgenden Evaluationsbogen zum Lernbaustein auszufüllen:

>[Feedback zum Lernbaustein](https://studfeedback.uni-kiel.de/evasys/online.php?p=HL3CT)

Alle Angaben werden anonym erhoben. Die Teilnahme sowie die Beantwortung einzelner Fragen ist selbstverständlich freiwillig.

Herzlichen Dank für Ihre Teilnahme!

# Quellen

Konzeption und Inhalte dieses Lernbausteins basieren auf folgenden Quellen:

* Biernacka, Katarzyna, Buchholz, Petra, Danker, Sarah Ann, Dolzycka, Dominika, Engelhardt, Claudia, Helbig, Kerstin, Jacob, Juliane, Neumann, Janna, Odebrecht, Carolin, Petersen, Britta, Slowig, Benjamin, Trautwein-Bruns, Ute, Wiljes, Cord, & Wuttke, Ulrike. (2021). Train-the-Trainer-Konzept zum Thema Forschungsdatenmanagement (Version 4). Zenodo.; https://doi.org/10.5281/zenodo.5773203

* Helbig, Kerstin (2017): Einführung in das Forschungsdatenmanagement, RDA-DE-Trainings-Workshop; online unter https://www.forschungsdaten.org/images/1/1b/Einf%C3%BChrung-in-das-Forschungsdatenmanagement.pdf

* Jackenkroll, Martina (2021): Wie organisiere ich meine Dateien und Ordner? Einführung in das Forschungsdatenmanagement; online unter https://www.tu-chemnitz.de//ub/dokumente/open_access/fdm/2021_02_26_ZfwN_FDM.pdf

* Petersen, Britta, Engelhardt, Claudia, Hörner, Tanja, Jacob, Juliane, Kvetnaya, Tatiana, Mühlichen, Andreas, Schranzhofer, Hermann, Schulz, Sandra, Slowig, Benjamin, Trautwein-Bruns, Ute, Voigt, Anne, & Wiljes, Cord. (2022). Lernzielmatrix zum Themenbereich Forschungsdatenmanagement (FDM) für die Zielgruppen Studierende, PhDs und Data Stewards (Version 1). Zenodo. https://doi.org/10.5281/zenodo.7034478

* The Carpentries (2018): File Organization; online unter https://datacarpentry.org/rr-organization1/, letzer Zugriff 10.10.2022

* University of Pitsburgh: Oranizing Data; https://pitt.libguides.com/managedata/organizingdata, letzer Zugriff 10.10.2022

* nestor. Mein digitales Archiv.de: Dateiablage und Dateinamen; https://meindigitalesarchiv.de/infos-und-tools/dateiablage-und-dateinamen/, letzer Zugriff 10.10.2022

* The University of Kansas: Organize Your Data; https://lib.ku.edu/data/organize, letzer Zugriff 10.10.2022

* University of New Hampshire: Organizing Data ; https://libraryguides.unh.edu/datamanagement/organize, letzer Zugriff 10.10.2022

* University of Bath: Organizing Data; https://library.bath.ac.uk/research-data/working-with-data/organising-data, letzer Zugriff 10.10.2022

* University of Cambridge: Organizing your data; https://www.data.cam.ac.uk/data-management-guide/organising-your-data, letzer Zugriff 10.10.2022

* Harvard Medical School: File Naming Convetions; https://datamanagement.hms.harvard.edu/collect/file-naming-conventions, letzer Zugriff 10.10.2022
