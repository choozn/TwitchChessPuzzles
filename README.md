# Chat Commands

| Command| Nutzbar von|Auswirkung|
| ------------- |:-------------:| :-----|
| `!skip` | Moderator | Überspringt das aktuelle Puzzle |
| `!reload` | Moderator | Startet das Spiel neu - Punkte bleiben erhalten |
| `!hard-reset` | Moderator | Startet das Spiel komplett neu - Punkte werden zurückgesetzt (nutzbar als Notlösung im Falle eines Crashs) |
| `!mode [mode]` | Moderator | Setzt den Spielmodus - mögliche Modi sind unten aufgeführt (Beispiel: !mode 5)|
| `!new` | Moderator | Startet ein neues Spiel |
| `!rotation` | Moderator | Aktiviert / deaktiviert das Rotieren des Boards nach zu spielender Farbe|

| Mode | Beschreibung |
| ------------- |:-------------:|
| `1` | Schachmatt in einem Zug |
| `2` | Schachmatt in zwei Zügen |
| `3` | Schachmatt in drei Zügen |
| `4` | Schachmatt in vier Zügen |
| `5` | Schachmatt in fünf Zügen |
| `random` | Schachmatt in einer wechselnden Anzahl an Zügen |
| `best` | Finde den besten Zug - keine Schachmatt-Rätsel |

# Schritt für Schritt Anleitung - Setup von TwitchChessPuzzles

### Schritt 1. - OBS öffnen

### Schritt 2. - Eine neue Szene erstellen
![Anleitung - 1](https://i.imgur.com/jSHgw6q.png)

![Anleitung - 2](https://i.imgur.com/xkfvluf.png)

### Schritt 3. - Eine neue Quelle hinzufügen
![Anleitung - 3](https://i.imgur.com/wqROjkg.png)

![Anleitung - 4](https://i.imgur.com/XI0mJCc.png)

![Anleitung - 5](https://i.imgur.com/c4pGGBq.png)

### Schritt 4. - TwitchChessPuzzles einbinden

![Anleitung - 6](https://i.imgur.com/GLBgm1e.png)
- Falls Teile der Einstellungen fehlen muss entweder nach unten gescrollt, oder das Fenster nach unten länger gezogen werden.
- Die einzutragende URL lautet `https://chess.choozn.dev/?c=[CHANNEL]`
- Hier muss [CHANNEL] mit dem Namen des Twitch Kanals ersetzt werden. Zum Beispiel `https://chess.choozn.dev/?c=JanistanTV`
- Auch die Größe muss richtig eingestellt werden. Die Breite muss `1920` und die Höhe `1080` betragen.

### Schritt 5. - Fertig!

![Anleitung - 7](https://i.imgur.com/QLtVUTQ.png)
- Der Chat kann nun mit Chatnachrichten im Format der (englischen!) [Algebraischen Notation](https://de.wikipedia.org/wiki/Schachnotation#Algebraische_Notation) teilnehmen. Alle möglichen legalen Züge werden in der Liste rechts vom Schachboard aufgelistet.

Hurray - Schon geschafft :D

### Fehlerbehebung
- Bei Fehlern, wie einem verbuggten Puzzle o.Ä., kann im Chat mit `!skip` oder `!reload` als Mod das fehlerhafte Puzzle übersprungen werden.

-> Bei Fragen oder Sonstigem Discord: choozn#6498

(Fotostrecke auch unter https://imgur.com/a/ARKt5pa)


----------------------------------------------------
Icons by https://www.flaticon.com under the Flaticon License
-> Made by FreePik
