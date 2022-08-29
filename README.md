# yaEmployeeManager

Projektbeschreibung

Mitarbeiter Datenverwaltungssystem mit fehlerkorrigierender Suchfunktion

Die Umsetzung der Datenbankanforderung erfolgt mit MySQL. Das Backend wird mithilfe einer Java-Applikation umgesetzt und das Frontend basiert auf dem Angular-Framework. 

Ist-Zustand
Firma Kamalyon benötigt ein Verwaltungssystem für ihre Mitarbeiter. Bisher wurden diese in analoger Form gesichert. Da der Mitarbeiterbestand in den letzten Monaten rasant gestiegen ist, besteht die Nachfrage, die Daten zu digitalisieren. 

Soll-Zustand
Die Applikation soll einfach gestaltet werden, um die bisher wenig Technik affinen Mitarbeiter anzulernen. Alle wichtigen Mitarbeiterdaten sollen zentral aufgeführt und abgespeichert und über digitale Endgeräte jederzeit abgerufen werden können. 

Damit Mitarbeiter problemlos, auch mit rechtschreibfehlerbehafteten Suchanfragen, die gewünschten Suchergebnisse erzielen können, gibt es eine fehlerkorrigierende Suchfunktion namens Fuzzy.

Die Firma Kamalyon hat bis dato 53 Mitarbeiter. Um die Daten gemäß zu erfassen, bleiben wir mit der Firma stetig in regem Kontakt. Um den Datenschutz zu gewährleisten, werden alle Mitarbeiterdaten vertraulich behandelt und in einer verschlüsselten Datenbank gespeichert.
 
Die Haupttabelle wird Mitarbeiter heißen. Darin enthalten
sind die MitarbeiterID, der Vor- und Nachname des Mitarbeiters, das Geburtsdatum, die AbteilungsID, die StellenID, sowie die Gehaltsklasse.

Bei der AbteilungsID und der StellenID handelt es sich um Untertabellen. Die Abteilungstabelle enthält die verschiedenen Abteilungen, um die verschiedenen Mitarbeiter zu gruppieren.
Die Stellentabelle hingegen bezeichnet die einzelnen Stellen der Mitarbeiter, die aus der  StellenID und Stellenbeschreibung besteht. Mithilfe dieser Tabelle schafft man einen guten Überblick über die Aufgabenbereiche der Mitarbeiter.
Da die Firma Kamalyon einen Tarifvertrag hat, gibt es eine Gehaltstabelle, die die verschiedenen Gehaltsklassen und deren entsprechenden Gehälter beinhaltet. 

Um noch einen genaueren Überblick zu schaffen, gibt es eine weitere Tabelle, die die Projekte der Firma beinhaltet. Darin enthalten sind die ProjektIDs und die Bezeichnungen der Projekte, sowie das Startdatum und Enddatum des Projektes.


Um mehrere Projekte mehreren Mitarbeitern zuzuweisen, gibt es zudem eine Mitarbeiter-Projekt-Zuweisungstabelle, die beliebig viele Mitarbeiter beliebig vielen Projekten zuweisen kann. 

Um optimal arbeiten zu können, arbeitet unser Team agil. 
Unser Projekt ist insgesamt für 60h angesetzt. Aus diesem Grund ist Projektende gegen Ostern 2023.
 

Zeitaufwand in h	Bezeichnung	Erläuterung 
30	Entwicklung (Frontend und Backend)	
10	Dokumentation	WiPO -> Programmablaufplan, GANTT; Was fehlt noch? Offene Themen..?; Bedienungsanleitung?, Pflichten und Lastenheft, Kosten-/Nutzenrechnung
10	Datenbankentwicklung	Er-Modell erstellen, Umsetzung der Datenbank(anbindung)
5	Anbindungen	GitHub, Server, Frontent-Backend-, Datenbank-Verknüpfung
5	Testen	Welches Verfahren

![image](https://user-images.githubusercontent.com/71440090/187171960-c5898a12-65ab-4eef-8e99-cdd227898b58.png)
