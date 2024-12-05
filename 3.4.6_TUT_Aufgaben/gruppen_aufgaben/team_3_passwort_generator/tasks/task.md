# Gruppenprojekt: Passwort Generator als Konsolenprogramm


## Ziel des Projekts

In diesem Gruppenprojekt werdet ihr gemeinsam ein einfaches *Passwort Generator als Konsolenanwendung entwickeln*. Der Schwerpunkt liegt darauf, die in den letzten Wochen erlernten Programmierkonzepte anzuwenden und eure Zusammenarbeit im Team zu stärken. Es ist nicht notwendig, ein vollständig ausgereiftes Produkt zu erstellen. Stattdessen sollt ihr euch darauf konzentrieren, Schritt für Schritt vorzugehen und sicherzustellen, dass alle Teammitglieder aktiv mitarbeiten.


## Aufgabenstellung

Eure Aufgabe ist es, als Gruppe einen Passwort Generator zu entwickeln, bei dem der Benutzer sich ein Passwort zufällig generieren lassen kann, um es in einer Applikation zu benutzen. (Beachtet dazu die Hilfestellung unten.)
Der Umfang des Generators kann schrittweise erweitert werden, wobei ihr die verschiedenen Funktionen nach und nach implementiert.

**Euer Code kommt in den solution Ordner.**


## Mögliche Funktionen

Hier sind einige Funktionen, die ihr in euer Passwort Generator integrieren könnt:

- **Passwort generieren:** Ist zugegeben der offensichtliche Teil. Hier könnt ihr euch als Team überlegen, ob ihr zunächst eins mit einer festen Länge generieren lassen wollt oder diese auch vom User vorgeben lasst. Zum testen könnt ihr auch zunächst nur eine zufällige Zahl auf Abruf generieren lassen. 

    *Erweiterungen:*

- **Passwörter speichern:** Speichert Passwörter und die dazugehörige Website und giebt sie dem User passen zurück.
- **Buchstaben im Passwort:** Fällt euch eine Möglichkeit ein ausser Zahlen auch Buchstaben zu generieren? :)
- **Zusätzliche ausgabe Möglichkeiten:** Gebt zum User zb die möglichkeit seine ganze Passwortliste auszugeben.

    *Hilfestellung*
Eine Zufallszahl könnt ihr in Dart mit dem Math-Package generieren lassen:

      import 'dart:math';

      Random random = new Random();
      int randomNumber = random.nextInt(100); // von 0 bis 99 


## Umsetzung

Im Solution-Order giebt es bereits ein Gerüst um das Programm umzusetzen. Besprecht euch bevor ihr anfangt zunächt welche Funktionen ihr umsetzen wollt und welche Teile des Gerüstes ihr verwenden möchtet. (Ihr könnt alles nach belieben ändern, löschen etc.)
Natürlich ist es euch auch freigestellt ganz von vorne anzufangen und ohne Hilfestellung ein eigenes main.dart zu verfassen. Wendet euch im zweifelsfall an den Tutor und probiert euch aus.


## Zu verwendende Konzepte

Ihr dürft alle bisher gelernten Konzepte nutzen, um das Spiel zu entwickeln. Hier sind einige Beispiele:

- **Schleifen:** Nutzt Schleifen, um durch die Fragen zu iterieren oder um dem Benutzer mehrere Versuche zu geben.
- **Komplexe Datentypen:** Verwendet Listen, Maps oder andere geeignete Datenstrukturen zur Speicherung der Fragen und Antworten.
- **Nutzereingaben:** Erfasst die Antworten des Benutzers über die Konsole und wertet diese aus.


## Tipps für die Zusammenarbeit

- **Aufgabenverteilung:** Am besten macht ihr euch als Team einen kleinen Plan, und jeder übernimmt einen Teil.
- **Gegenseitige Unterstützung** Denkt daran, ihr seid ein Team, arbeitet zusammen.


## Viel Erfolg!

Nutzt dieses Projekt, um das Gelernte praktisch anzuwenden und gleichzeitig eure Teamfähigkeit zu stärken. Denkt daran, dass der Weg das Ziel ist – es geht nicht nur darum, ein funktionierendes Spiel zu erstellen, sondern auch darum, als Gruppe zusammenzuarbeiten und voneinander zu lernen.
