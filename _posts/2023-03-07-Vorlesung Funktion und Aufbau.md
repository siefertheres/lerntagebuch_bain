---
title: "Vorlesung Aufbau und Funktion von Bibliothekssystemen 1/2"
date: 2023-03-07
---

### Ablauf der Einheit:
-	Metadatenstandards
-	Koha


#### Metadatenstandards: 
##### Was sind Metadatenstandards?
<p> Metadatenstandards sind verpflichtende Regelungen für Metadaten. Sie werden genutzt, um ein gemeinsames Verständnis für die Bedeutung und Semantik der Daten sicherzustellen, sowie die richtige Verwendung und Interpretation, sowohl seitens der Ersteller*innen, als auch seitens der Nutzer*innen. Dafür werden gewisse Kriterien festgelegt, welche die Daten definieren – diese werden dann Metadaten genannt. Es gibt drei Arten von Metadatenstandards [^1] :
-	Beschreibende Metadaten
-	Strukturelle Metadaten
-	Administrative Metadaten

Metadaten werden sehr häufig in SGML (Standard Gerneralized Markup Language) oder XML beschrieben. </p>
In Bibliotheken werden ebenfalls Metadaten bzw. Metadatenstandards für die Katalogisierung verwendet. Besonders bekannt sind MARC21, GND (Gemeinsame Normdatei) sowie der Dublin Core (DCMI - Dublin Core Metadata Initiative). Die GND wird verwendet um Normdaten kooperativ nutzen und verwalten zu können - dabei beschränkt sie sich nicht nur auf Bibliotheken sondern schliesst auch Archive, Museen sowie Kultur- und Wissenschaftseinrichtungen mit ein [^2].
##### MARC21
1. Was ist MARC21?
<p> MARC21 (Machine-Readable Cataloging) ist ein Medataten-Standard, welcher 1999 in der Library of Congress  unter dem Namen „ MARC21 Format for bibliographic Data“  erstellt wurde. Ziel des Standards ist die Repräsentation und der Austausch von bibliografischen Informationsdaten in einem machschienenlesbaren Format [^3] . Dabei besteht ein Datensatz aus drei Elementen:

![image](https://github.com/siefertheres/lerntagebuch_bain/assets/92806411/5377d19c-5176-4c8b-aae1-548f86effae4) [^4]

Es ermöglicht die Beschreibung von diversen Trägerdateien, wie Bücher, Periodika, Karten, Musik, Videos und Computerdateien. Das Schema, mit welchem die Daten beschrieben werden ist das XML-Schema *MARCXML*. Es ist ein einfaches Schema, dass flexibel und leicht erweiterbar ist [^5]. 
</p> 

3. Was ist der Vorteil?
Vorteile liegen darin, dass sich eine vielzahl von katalogisierungsregelungen abbildenlassen (Flexibilität). Ein weiterer grosser Vorteil ist, dass es sich für Dokumente aller Art eignet. Ausserdem ist durch seine grosse Verbreitung ein (leichterer) internationaler Austausch  möglich.
 
5. Wie und wo wird es eingesetzt?
<p>Wie bereits etwas weiter oben erwähnt ist das Format International, und wid auch international genutzt. Jedoch ist hier anzumerken, dass in vielen Ländern und Communitys abgeänderte Versionen verwendet werden. MaRC21 wird zum Katalogisieren sowie zum Austausch verwendet. </p>
7. Regelwerk vs. Datenformat
<p>
Regelwerk ist die theoretische Grundlage und legt fest *wie* etwas zu beschreiben ist (RDA oder RAK-WB). Das Dateiformat legt fest aauf welche Art es zu beschreiben ist d.h. wie die praktische Repräsentation aussehen soll. Dies geschieht durch Datentypen und Strukturen(MARC21).
</p>





##### Bibliothekssoftware Koha
Koha ist ein Open-Source-Projekt des Horowhenua Library Trust, welches kostenlos nutzbar ist. Das Projekt bzw. das System ist community-basiert und wurde 1999 in Neuseeland gestartet. Ein Jahr später wurde die Koha 1.00 Version zum Download zur Verfügung gestellt [^6]. Die Software bietet grundlegende Funktionen wie Verwaltung, Katalogisierung und Ausleihe.  

##### Übung im Unterricht
Im Unterricht wurde eine Übung zur manuellen Bedienung durchgeführt. Dabei sollte der Workflow einer Bibliothek abgebildet werden. Dabei wurden Ausleihe/Rückgabe, Katalogierung und Benutzererfassung getestet. Alle aufgaben konnten ohne Probleme gemacht werden.
![Benutzer anlegen](https://github.com/siefertheres/lerntagebuch_bain/assets/92806411/afe03918-bcd9-4c92-877f-6ecb35c0c5b8)

![Buch katalogisieren](https://github.com/siefertheres/lerntagebuch_bain/assets/92806411/43f4d0c1-086e-4613-9911-80d08f5c8b18)

![Buch ausleihen](https://github.com/siefertheres/lerntagebuch_bain/assets/92806411/5b1cffe9-0f15-448e-9ae5-1cd936c956c7)
![Buch zurückgeben](https://github.com/siefertheres/lerntagebuch_bain/assets/92806411/040cd1df-6427-4eb9-90fd-a890bab93148)

[^1]: [Metadaten Wikipedia] (https://en.wikipedia.org/wiki/Metadata_standard#cite_note-1)
[^2]: [DNB - GND] (https://www.dnb.de/DE/Professionell/Standardisierung/GND/gnd_node.html)
[^3]: [MARC21] (https://www.loc.gov/marc/bibliographic/bdintro.html)
[^4]: [Quelle Bild] (https://www.slideshare.net/PRABHAKARSHEKHAR/marc-21-90298315)
[^5]: [DDBinfo für Daten] (https://wiki.deutsche-digitale-bibliothek.de/pages/viewpage.action?pageId=78513053)
[^6]: [Koha] (https://koha-community.org/about/koha-project-organization/)
