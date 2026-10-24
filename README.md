# Bögen

Formulare des Notariats, als Webseite unter https://twoinar.github.io/boegen/.

- `vorgespraech.html` – Vorgesprächsbogen mit Bedarfsbewertung und Anbindung an den GNotKG-Kostenrechner (https://twoinar.github.io/kostenrechner/). Eingaben bleiben im Browser bzw. im gespeicherten PDF.
- `vorgespraech-maske.html` – derselbe Vorgesprächsbogen als Maske zum Durchklicken (1 Vorgang, 2 Beteiligte, 3 Grundstücke (Abruf von Flurstück, Fläche, Bebauung und Bodenrichtwert per Anschrift aus ALKIS/BORIS, Grundbuch nur von Hand) und freier Sachverhalt zum Diktieren, 4 Berechnungen, 5 Auftrag, 6 Abschluss; „Alles aufklappen“ zeigt alles auf einer Seite). Erzeugt das PDF im Design des Vorgesprächsbogens ohne Formularfelder, mit Unterschriftszeilen, zum elektronischen Unterschreiben; eigener Ablageordner. Die Eingaben stecken als Daten im PDF (Schlüssel `WoinarMaske`), ältere Vorgesprächsbögen lassen sich öffnen. Gebaut aus `vorgespraech.html` (Berechnungsmodule unverändert übernommen).
