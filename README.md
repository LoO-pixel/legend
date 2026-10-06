# Legend of _

Ein Survivor-Roguelite für den Browser im Stil eines alten Zeitungsdrucks: schwarz, grau, Papier – und ein wenig Rot.
Der Strich im Titel ist dein Name. Kurz: **Lo_**.

**Spielen:** https://loo-pixel.github.io/legend/

![Icon](icon.png)

## Worum es geht

Du bist eine winzige Figur in einer großen, zufällig erzeugten Landschaft. Feinde kommen von selbst, deine Waffen feuern von selbst – du läufst, sammelst und entscheidest.

- Jede Ebene dauert **5 Minuten**. Dann kommt der Knochenkönig.
- Ist er besiegt, öffnet sich ein Tor. Du hast **25 Sekunden**, sonst holt dich die Dunkelheit.
- Hinter dem Tor liegt die nächste Ebene: neue Karte, neue und stärkere Gegner.
- Bei jedem Stufenaufstieg wählst du eine von drei Karten. Platz ist für höchstens 10 Waffen und Fähigkeiten.
- Gold bleibt nach dem Tod erhalten und wird beim Krämer zu dauerhaften Verbesserungen.

## Was es in der Welt gibt

- Stadt, Dörfer, Straßen, Brücken, Seen, Flüsse (durchwatbar, aber langsam), Wälder, Berge
- Kirche und Kapellen heilen ein wenig – solange ihre Fenster offen sind
- Friedhöfe, Mühlen, Ruinen, Türme und Steinkreise bergen Proviant oder Fundstücke
- Ein Opferaltar mit Magnet, bewacht von der Fleischkugel
- Ein Stall: für 25 Gold gibt es ein Pferd, einmal pro Ebene
- Manche Welten haben ein riesiges Monument: Weltenbaum, Burg, Säule, Statue oder Gruft

Alles Weitere steht im **Almanach** im Hauptmenü.

## Steuerung

| Gerät | Bewegen | Sonst |
| --- | --- | --- |
| iPhone / iPad | Finger aufs Bild legen und ziehen | Knöpfe für Karte und Pause |
| PC | WASD oder Pfeiltasten | Maus für Karte, Pause und Menüs |

Angegriffen wird automatisch.

## Seeds

Jede Welt entsteht aus einer Zahl. Gleicher Seed, gleiche Welt. Im Menü kannst du würfeln, einen Seed eintippen oder einen Link kopieren und weitergeben.

## Auf den Homescreen

In Safari: Teilen → „Zum Home-Bildschirm“. Dann läuft das Spiel im Vollbild.

## Speichern

Der Spielstand liegt nur in deinem Browser (IndexedDB). Es gibt kein Konto und keinen Server. Wer die Browserdaten löscht, löscht auch den Stand. Im privaten Modus kann Safari das Speichern verweigern; das Menü weist dann darauf hin.

## Technik

- Eine einzige `index.html`, reines JavaScript und Canvas, kein Build-Schritt, keine Bibliotheken
- Daneben liegen nur `musik.mp3` und `icon.png`
- Das Bild wird in Software gezeichnet und per Raster auf drei Töne plus Rot gebracht

Zum Selberhosten genügt es, die drei Dateien in ein Verzeichnis zu legen.

## Credits

- Idee und Spiel: me
- Code: mit Claude (Anthropic) und mir entstanden
- Musik: „Shadow Riff“, erzeugt mit Suno
- Boss-Figur (Knochenkönig): [Sword Skeleton – Pixel Art Character](https://sanctumpixel.itch.io/sword-skeleton-pixel-art-character) von Sanctumpixel

Projektseite: https://loo-pixel.github.io/legend/
