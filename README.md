# Legend of _

![Icon](icon.png)

**Play / Spielen:** https://loo-pixel.github.io/legend/

[English](#english) · [Deutsch](#deutsch)

---

## English

A survivor roguelite for the browser in the style of an old black-and-white print: black, grey, paper – and a little red.
The line in the title is your name. **Lo_** for short.

The game starts in English. German can be chosen under **Settings → Language**.

### What it's about

You are a tiny figure in a large, randomly generated landscape. Enemies come by themselves and your weapons fire by themselves. You walk, collect and decide.

- Six stages in two landscapes: stages 1–3 in the Greenlands, stages 4–6 in the Desert. After stage 6 comes “Fin”.
- Every stage lasts **5 minutes**. Then the boss arrives: the Bone King, the Forest Spirit and the Cacodemon in the Greenlands; the Tomb Warden, the Sand Goblin and the Desert Eye in the Desert.
- In each landscape it gets darker from stage to stage; lanterns along the roads and your own light help.
- Once the boss is defeated, a gate opens. You have **25 seconds**, or the darkness takes you.
- Beyond the gate lies the next stage: a new map, new and stronger enemies.
- On every level-up you choose one of three cards. There is room for at most 10 weapons and abilities.
- Three shrines per stage hold a random blessing: double XP, invulnerability, double gold, double damage – or a wave of enemies or a curse.
- In endless mode (unlocked after stage 3) every stage comes from either landscape at random, and all seven bosses can appear, including the Mushroom Lord, who only lives there.
- Gold is kept after death. At the merchant you buy permanent upgrades and fill the armory: at first there is only a starter kit, and every further weapon, ability, boss power and blueprint for the smith has to be bought first. An ankh lets you rise again once.
- The settings let you switch music, curvature, shadows, clouds, bloom, sand drifts and the bought second starting weapon on and off. Color mode is added after stage 6.

### What's in the world

- A town, villages, roads, bridges, lakes, rivers (you can wade through, but slowly), forests, mountains
- Church and chapels heal a little – as long as their windows are open
- Graveyards, mills, ruins, towers and stone circles hold provisions or finds
- A sacrificial altar with a magnet, guarded by the Flesh Orb
- A stable: a horse for 25 gold, once per stage
- A smith: for 60 gold he fuses two weapons from level III into a forgework – there are 16 works, one per stage
- A pet shop in the main menu: a cat, dog, llama or slime comes along, one per run. Pets learn with you and keep their level
- Some worlds have a giant landmark: World Tree, Giant Castle, Giant Pillar, Colossal Statue, Necropolis – in the desert also a pyramid
- The Desert: sand and dunes, oases with palms, dry riverbeds, red rock plateaus, adobe houses, cacti, high rock walls all around

Everything else is in the **Almanac** in the main menu.

### Controls

| Device | Move | Other |
| --- | --- | --- |
| iPhone / iPad | Put your finger on the screen and drag | Buttons for map and pause |
| PC | WASD or arrow keys | Mouse for map, pause and menus |

Attacks happen automatically.

### Seeds

Every world grows from a number. Same seed, same world. In the menu you can roll, type in a seed or copy a link and pass it on.

### On the home screen

In Safari: Share → “Add to Home Screen”. The game then runs in fullscreen.

### Saving

Your progress lives only in your browser (IndexedDB). There is no account and no server. Clearing your browser data also clears your progress. In the settings you can reset your progress on purpose; settings and name are kept. In private mode Safari may refuse to save; the menu tells you when that happens.

### Technology

- A single `index.html`, plain JavaScript and canvas, no build step, no libraries
- Next to it only `musik.mp3` (Greenlands), `music2.mp3` (Desert) and `icon.png`
- The picture is drawn in software and dithered down to three tones plus red

To host it yourself, put the four files into one folder.

### Credits

- Idea and game: Olfbert
- Code: made with Claude (Anthropic)
- Music, Greenlands: “Shadow Riff”, made with Suno AI
- Music, Desert: “Descent of the Sands”, made with Suno AI
- Boss (Bone King): [Sword Skeleton – Pixel Art Character](https://sanctumpixel.itch.io/sword-skeleton-pixel-art-character) by Sanctumpixel
- Boss (Forest Spirit): [The Forest Spirit](https://pidroudays.itch.io/the-forest-spirit) by pidroudays
- Boss (Cacodemon): [2D Pixel Art Cacodaemon Sprites](https://elthen.itch.io/2d-pixel-art-cacodaemon-sprites) by Elthen
- Boss (Tomb Warden): Skeleton from [Monsters Creatures Fantasy](https://luizmelo.itch.io/monsters-creatures-fantasy) by Luiz Melo
- Boss (Sand Goblin): Goblin from [Monsters Creatures Fantasy](https://luizmelo.itch.io/monsters-creatures-fantasy) by Luiz Melo
- Boss (Desert Eye): Flying Eye from [Monsters Creatures Fantasy](https://luizmelo.itch.io/monsters-creatures-fantasy) by Luiz Melo
- Boss (Mushroom Lord, endless mode only): Mushroom from [Monsters Creatures Fantasy](https://luizmelo.itch.io/monsters-creatures-fantasy) by Luiz Melo

---

## Deutsch

Ein Survivor-Roguelite für den Browser im Stil eines alten Schwarzweißdrucks: schwarz, grau, Papier – und ein wenig Rot.
Der Strich im Titel ist dein Name. Kurz: **Lo_**.

Das Spiel startet auf Englisch. Deutsch lässt sich unter **Settings → Language** (Einstellungen → Sprache) wählen.

### Worum es geht

Du bist eine winzige Figur in einer großen, zufällig erzeugten Landschaft. Feinde kommen von selbst, deine Waffen feuern von selbst – du läufst, sammelst und entscheidest.

- Sechs Ebenen in zwei Landschaften: Ebene 1–3 im Grünland, Ebene 4–6 in der Wüste. Nach Ebene 6 heißt es „Fin“.
- Jede Ebene dauert **5 Minuten**. Dann kommt der Boss: Knochenkönig, Waldgeist und Kakodämon im Grünland; Grabwächter, Sandgoblin und Wüstenauge in der Wüste.
- In jeder Landschaft wird es von Ebene zu Ebene dunkler; Laternen an den Straßen und dein eigener Lichtschein helfen.
- Ist der Boss besiegt, öffnet sich ein Tor. Du hast **25 Sekunden**, sonst holt dich die Dunkelheit.
- Hinter dem Tor liegt die nächste Ebene: neue Karte, neue und stärkere Gegner.
- Bei jedem Stufenaufstieg wählst du eine von drei Karten. Platz ist für höchstens 10 Waffen und Fähigkeiten.
- Drei Schreine je Ebene bergen eine zufällige Gabe: doppelte Erfahrung, Unverwundbarkeit, doppeltes Gold, doppelter Schaden – oder eine Feindeswelle oder einen Fluch.
- Im Endlosmodus (frei nach Ebene 3) kommt jede Ebene zufällig aus einer der beiden Landschaften, und alle sieben Bosse können auftreten – auch der Pilzfürst, den es nur dort gibt.
- Gold bleibt nach dem Tod erhalten. Beim Krämer kaufst du damit dauerhafte Verbesserungen und füllst die Waffenkammer: Zu Beginn gibt es nur ein Startpaket, jede weitere Waffe, Fähigkeit, Boss-Kraft und jeder Bauplan für den Schmied wird erst gekauft. Mit einem Ankh stehst du einmal wieder auf.
- In den Einstellungen lassen sich Musik, Wölbung, Schatten, Wolken, Bloom, Sandwehen und die gekaufte zweite Startwaffe ein- und ausschalten. Nach Ebene 6 kommt der Farbmodus dazu.

### Was es in der Welt gibt

- Stadt, Dörfer, Straßen, Brücken, Seen, Flüsse (durchwatbar, aber langsam), Wälder, Berge
- Kirche und Kapellen heilen ein wenig – solange ihre Fenster offen sind
- Friedhöfe, Mühlen, Ruinen, Türme und Steinkreise bergen Proviant oder Fundstücke
- Ein Opferaltar mit Magnet, bewacht von der Fleischkugel
- Ein Stall: für 25 Gold gibt es ein Pferd, einmal pro Ebene
- Ein Schmied: für 60 Gold verschmilzt er zwei Waffen ab Stufe III zu einem Schmiedewerk – 16 Werke gibt es, eines je Ebene
- Eine Tierhandlung im Hauptmenü: Katze, Hund, Lama oder Schleim begleitet dich, immer nur eines je Lauf. Tiere lernen mit und behalten ihre Stufe
- Manche Welten haben ein riesiges Wahrzeichen: Weltenbaum, Riesenburg, Riesensäule, Kolossstatue, Nekropole – in der Wüste auch eine Pyramide
- Die Wüste: Sand und Dünen, Oasen mit Palmen, trockene Flussbetten, rote Felsplateaus, Lehmhäuser, Kakteen, ringsum hohe Felswände

Alles Weitere steht im **Almanach** im Hauptmenü.

### Steuerung

| Gerät | Bewegen | Sonst |
| --- | --- | --- |
| iPhone / iPad | Finger aufs Bild legen und ziehen | Knöpfe für Karte und Pause |
| PC | WASD oder Pfeiltasten | Maus für Karte, Pause und Menüs |

Angegriffen wird automatisch.

### Seeds

Jede Welt entsteht aus einer Zahl. Gleicher Seed, gleiche Welt. Im Menü kannst du würfeln, einen Seed eintippen oder einen Link kopieren und weitergeben.

### Auf den Homescreen

In Safari: Teilen → „Zum Home-Bildschirm“. Dann läuft das Spiel im Vollbild.

### Speichern

Der Spielstand liegt nur in deinem Browser (IndexedDB). Es gibt kein Konto und keinen Server. Wer die Browserdaten löscht, löscht auch den Stand. In den Einstellungen lässt sich der Fortschritt auch gezielt zurücksetzen – Einstellungen und Name bleiben dabei. Im privaten Modus kann Safari das Speichern verweigern; das Menü weist dann darauf hin.

### Technik

- Eine einzige `index.html`, reines JavaScript und Canvas, kein Build-Schritt, keine Bibliotheken
- Daneben liegen nur `musik.mp3` (Grünland), `music2.mp3` (Wüste) und `icon.png`
- Das Bild wird in Software gezeichnet und per Raster auf drei Töne plus Rot gebracht

Zum Selberhosten genügt es, die vier Dateien in ein Verzeichnis zu legen.

### Credits

- Idee und Spiel: Olfbert
- Code: mit Claude (Anthropic) entstanden
- Musik Grünland: „Shadow Riff“, erzeugt mit Suno AI
- Musik Wüste: „Descent of the Sands“, erzeugt mit Suno AI
- Boss-Figur (Knochenkönig): [Sword Skeleton – Pixel Art Character](https://sanctumpixel.itch.io/sword-skeleton-pixel-art-character) von Sanctumpixel
- Boss-Figur (Waldgeist): [The Forest Spirit](https://pidroudays.itch.io/the-forest-spirit) von pidroudays
- Boss-Figur (Kakodämon): [2D Pixel Art Cacodaemon Sprites](https://elthen.itch.io/2d-pixel-art-cacodaemon-sprites) von Elthen
- Boss-Figur (Grabwächter): Skeleton aus [Monsters Creatures Fantasy](https://luizmelo.itch.io/monsters-creatures-fantasy) von Luiz Melo
- Boss-Figur (Sandgoblin): Goblin aus [Monsters Creatures Fantasy](https://luizmelo.itch.io/monsters-creatures-fantasy) von Luiz Melo
- Boss-Figur (Wüstenauge): Flying Eye aus [Monsters Creatures Fantasy](https://luizmelo.itch.io/monsters-creatures-fantasy) von Luiz Melo
- Boss-Figur (Pilzfürst, nur im Endlosmodus): Mushroom aus [Monsters Creatures Fantasy](https://luizmelo.itch.io/monsters-creatures-fantasy) von Luiz Melo

---

Project page / Projektseite: https://loo-pixel.github.io/legend/
