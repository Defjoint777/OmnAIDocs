
## Dokumentation – OmnAIView Projekt

## 1. Wie schreibe ich eine vernünftige Dokumentation für das OmnAIView-Projekt?

## 1.1 Art der Dokumentation

Zunächst müssen wir klar definieren, um welche Art der Dokumentation es sich handelt. Wir nehmen an, es handelt sich um eine lineare Projektdokumentation, was voraussetzt, dass in der Dokumentation folgende Kriterien erfüllt sind:

## 1.1.1 Strukturierte Reihenfolge

Die Inhalte des Projekts sollten in einer logischen Reihenfolge präsentiert werden. Dies dient dazu, eine klare Struktur des Dokuments zu schaffen und damit auch die Lesbarkeit des Endprodukts zu erhöhen.

## 1.1.2 Klare und präzise Sprache

Laut Recherchen im Internet (z. B. GitHub Copilot) sollte man Komplexität und Fachbegriffe vermeiden, wenn es nicht notwendig ist. In meiner Dokumentation werde ich jedoch Fachbegriffe verwenden, um die Präzision zu erhöhen und die Entstehung von Missverständnissen möglichst gering zu halten. Dennoch werde ich auf eine angemessene Lesbarkeit achten.

## 1.1.3 Schritt-für-Schritt-Darstellung

Im Idealfall ist das Dokument so aufgebaut, dass jeder Abschnitt den Leser auf den nächsten vorbereitet. Besonders schwer nachvollziehbare Inhalte können durch Diagramme oder andere Visualisierungsmittel unterstützt werden, um das Verständnis zu fördern.

## 1.1.4 Format und Konsistenz

Einheitliche Formatierung und Stil über den gesamten Verlauf der Dokumentation hinweg sind essenziell.

## 1.1.5 Quellen und Nachweise

Externe Informationen sollten durch Quellenangaben belegt werden.

## 1.2 Strukturierung des Inhalts

Um den Inhalt der Dokumentation sinnvoll und in logischer Reihenfolge zu gestalten, habe ich mir vorab folgende Leitfragen gestellt:

## 1.2.1 Was ist OmnAIView?

OmnAIView ist ein Modul innerhalb eines größeren Softwareprojekts, das dazu dient, vom Nutzer oder vom Gerät empfangene Daten (z. B. Wechselspannungen) in Form einer Vektorgrafik darzustellen.
 
Das Ziel dieses Moduls ist es, dem Endnutzer die Darstellung empfangener Daten in verschiedenen Formen zu ermöglichen. Was bedeutet das konkret?  

Betrachten wir das Beispiel einer Wechselspannung – wie ließe sich diese am sinnvollsten visualisieren? Richtig: ein Zeigerdiagramm wäre hier am verständlichsten.
  
Ein weiteres Beispiel:

Soll der Nutzer die Drehzahl eines Motors visualisieren, wäre ein Zeitverlaufsdiagramm wahrscheinlich die intuitivste und nachvollziehbarste Form der Darstellung.

Im Prinzip ist das die Aufgabe von OmnAIView: dem Nutzer die Möglichkeit zu bieten, verschiedene Endgeräte anzubinden und die empfangenen Daten in verschiedener Form visuell aufzubereiten.


## 1.2.2 Für wen ist OmnAIView gedacht?

Da es sich um ein Modul eines Softwareprojekts handelt, ist OmnAIView in verschiedensten industriellen Bereichen denkbar.

  
Welche Daten kann OmnAIView darstellen?

Das OmnAIView stellt einen Datenstrom aus timestamp:value Tupeln dar.
Das bedeutet alle Daten die in einem unbegrenztem Zeitraum produziert und empfangen sind(
z.B Lichtintensitätmessungen) können mit OmniAIView-Software in einem Format wie z.B 978350400(Unix timestamp):900Lx 
in einem Graph dargestellt werden.
   
Im Grossen und Ganzen: Jeder, der seine Zeitreihendaten in einem Graphen präsentieren möchte ist ein potenzieller Nutzer.

## 1.2.3 Was sind die Zeitreihendaten?

Unter Zeitreihendaten versteht man eine bestimmte Art von Daten, bei denen Beobachtungen in regelmässigen und kontinuierlichen Zeitraum erfasst werden.
Daten dieser Art sind von seiner Natur aus chronologisch und bilden zeitliche abfolge.
Zeitreihendaten begegnen uns täglich im Alltag z.B

- 01.01.2001 13:00:00 : 2.5°C
- 01.01.2002 13:00:00 : 3.5°C
- 01.01.2003 13:00:00 : 4.5°C

Daraus könnten wir eine Hervorsage tätigen dass am 01.01.2004 um 13:00:00 die Temperatur etwa um 1°C höher als um gleich Uhrzeit letztes Jahr ausfallen wird.
 
## 1.2.4 Für wen schreibe ich die Dokumentation?

Da es sich um ein Open-Source-Hard- und Softwareprojekt handelt, ist es wünschenswert, dass sich weitere Entwickler entscheiden, an der Entwicklung teilzunehmen.

Die Mitwirkung an dem Projekt setzt voraus, dass man über ausreichende fachliche Kenntnisse verfügt, um sich mithilfe der Dokumentation in das Projekt einzuarbeiten oder diese zumindest als unterstützendes Hilfsmittel beim Onboarding nutzen zu können.

Das Hauptziel der Dokumentation ist ein liniares, selbsterklärendes Handbuch bereitzustellen, welches innerhalb eines Tages gelesen und verstanden werden kann. Das Handbuch soll ermöglichen ein Überblick über Inhalt, Module, Schnittstellen, Begriffe und Design-Guidelines liefern.

Zurück zur Ausgangsfrage 1.0.0: "Wie schreibe ich eine vernünftige Dokumentation?"

Indem ich einfach anfange, die Dokumentation zu schreiben – und mich dabei aktiv mit der Materie auseinandersetze. 😉
