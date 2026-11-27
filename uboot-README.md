# U-BOOT ADVENTURE – Mission Titanic

V3-Build: Ein eigenständiges Tiefsee-Arcade-Spiel für Browser und GitHub Pages. Keine Installation, keine externen Bibliotheken.

## Starten
`index.html` herunterladen und im aktuellen Browser öffnen oder das Repository mit GitHub Pages veröffentlichen.

## Steuerung
- **Pfeil runter / S:** tiefer tauchen
- **Pfeil hoch / W:** auftauchen
- **Pfeil links/rechts / A / D:** seitlich bewegen
- **Leertaste / E:** Drucksystem stabilisieren (gedrückt halten)
- Auf Smartphone/Tablet die eingeblendeten Bildschirmtasten nutzen.

## Spielmechaniken
- Sammle goldene Münzen im Wasser und kaufe damit vier Upgrade-Typen.
- **Druckschutz:** erhöht die Druckgrenze.
- **Rumpfverstärkung:** erhöht die Rumpfreserve.
- **Sauerstofftank:** erhöht den Sauerstoffvorrat und reduziert den Verbrauch.
- **Motor:** verbessert die Steuerung.
- Die Werkstatt zeigt Upgrade-Stufen und Kosten. Die Tiefenanzeige schätzt die erreichbare Tiefe anhand deiner Ausrüstung.
- Anglerfische verursachen deutlich mehr Schaden als normale Fische.
- Warnanzeigen melden kritischen Druck, Sauerstoffmangel, Rumpfschäden und Kollisionen.
- Bei Rumpfversagen wird eine mehrstufige Implosionsanimation mit Lichtblitz, Schockwellen und Trümmern gezeigt.
- Ab 2.900 m erscheint das Titanic-Wrack; bei 3.800 m ist die Mission geschafft.

## GitHub Pages
1. ZIP entpacken und `index.html` sowie `README.md` in das Hauptverzeichnis deines GitHub-Repositories hochladen.
2. In **Settings → Pages** `Deploy from a branch` auswählen.
3. Branch `main` und Ordner `/ (root)` auswählen und speichern.

## Hinweis
Das Spiel ist Fiktion und keine realistische technische Simulation. Das Tauchboot ist eine stilisierte, Titan-inspirierte Arcade-Darstellung, keine maßstabsgetreue technische Rekonstruktion.


## V3 – Return to Surface
- Ohne Druckschutz- und Rumpf-Upgrades liegt die sichere Grenze bei 500 m.
- Unterhalb der persönlichen Tiefengrenze entsteht Druckschaden. Die Warnzentrale fordert zum sofortigen Auftauchen auf.
- Druckschutz und Rumpfverstärkung erhöhen gemeinsam die sichere Maximal-Tiefe. Die Tiefenanzeige entspricht dieser Grenze.
- Münzen erscheinen seltener; plane Sammelrouten und kaufe die nötigen Upgrades.
- Die Titanic ist als großes, zerbrochenes Passagierschiff mit Decks, vier Schornsteinen, Mast und Rumpfdetails dargestellt.
- Erreiche 3.800 m und kehre danach bis auf 80 m oder weniger zur Oberfläche zurück. Erst dann ist die Mission gewonnen.


## V3.1 – Cleaner GUI, dramatischere Warnungen, schnelleres Tauchen
- **Aufgeräumtes GUI:** schlanke Statusleiste (Tiefe, Druck, Rumpf, Sauerstoff, Münzen), kompakte Werkstatt unten, Bildschirmtasten nur noch auf Touch-Geräten. Die rote Markierung auf der Tiefenleiste zeigt die sichere Maximaltiefe.
- **Dramatischere Warnungen:** drei Alarmstufen mit pulsierendem/blinkendem Banner, rotem Randleuchten, Bildschirmwackeln, Risse im Sichtfenster bei niedrigem Rumpf, Sirene und Knarren (Ton mit **M** abschaltbar) sowie Countdown bis zum Rumpfbruch bzw. Sauerstoffende.
- **Schneller tauchen:** Abstieg ca. 1,5× so schnell (aktiv ca. 42 m/s, passiv ca. 7,5 m/s), Aufstieg ca. 45 m/s. Münzen erscheinen etwas häufiger, damit Upgrades trotzdem erreichbar bleiben.
- Fix: Hinweis-Einblendungen (Toast) verschwinden jetzt wieder.

## V3.2
- Noch etwas schnelleres Sinken (aktiv ca. 42 m/s).
- Der Sieg zählt erst nach der Rückkehr zur Oberfläche (80 m oder weniger). Nach Erreichen der Titanic zeigt das Banner dauerhaft die verbleibende Strecke nach oben an.
- Geheimer Cheat-Modus (Tastatur).

## V3.3
- **Dunkleres Wasser:** Je tiefer du tauchst, desto dunkler wird es; ab etwa 400 m leuchtet ein Scheinwerfer vor dem Boot.
- **Speedrun-Timer** in der Statusleiste. Sobald ein Cheat benutzt wird, ist die Zeitwertung für den Durchlauf aus. Die Bestzeit wird im Browser gespeichert.
- **Tiefenleiste** am rechten Rand: Das Boot sinkt mit, unten ist die Titanic. Der rote Bereich zeigt, wo die sichere Tiefe überschritten ist.
- Geheime Cheats (Tastatur).

## V4
- **Boot dreht sich** passend zur Blickrichtung und neigt sich beim Steigen/Sinken.
- **Meeresboden** mit Steinen und Seegras. Das Titanic-Wrack liegt jetzt darauf.
- **Hai:** erscheint einmal pro Runde (zwei Durchgänge) – ausweichen!
- **Zufallsereignisse** (mit Pausen dazwischen): Fischschwarm, Strudel, Geister-U-Boot, Münzregen, Stromausfall.
- **Skins:** Normal, Porsche 911, Alligator, Boss.
- Startet mit dem Schriftzug „Made by Lenn L.“.

## V4.1
- Ton robuster: wird bei der ersten Berührung/Taste freigeschaltet. Neue Töne für Münzen, Upgrades und Spielstart.

## V4.2
- **Hintergrundmusik** (live erzeugt): ruhige Akkorde und Melodie, die mit der Tiefe dunkler werden.
- **Ambiente:** Sonar-Ping, Blubbern, Walgesang in der Tiefe, Motorbrummen und tiefes Dröhnen.
- **Spannung:** Herzschlag bei Alarm, Hai-Motiv beim Hai, Fanfare beim Sieg.
- Musik an/aus mit **N** oder dem 🎵-Knopf, alle Töne mit **M**.

## V5
- **Menü:** Titelbildschirm mit Erfolgen & Fischdex, Bestenliste und Einstellungen (Musik, Effekte, Schwierigkeit). Pause mit Esc oder P.
- **Erfolge** (8) und **Fischdex** (8 Einträge), lokal gespeichert. Erfolge zählen nur ohne Cheats.
- **Bestenliste:** die 5 schnellsten Zeiten ohne Cheats.
- **Neu im Spiel:** Quallen (betäuben das Boot), Seeminen (ab 1.200 m), Sauerstoff-Blasen und Reparatur-Kits zum Einsammeln.
