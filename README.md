# Optik-Aufgabensammlung – Physik 8. Klasse

Eine interaktive Lern- und Übungsumgebung zum Teilgebiet **Optik** für die 8. Klasse.
Läuft komplett im Browser – **keine Installation, kein Server, keine Anmeldung, keine Cloud**.
Optimiert für den Einsatz auf **iPads** im Unterricht.

Kernstück ist die Datei `index.html` (Aufgabensammlung) mit vier eingebundenen, eigenständigen Simulationen.

---

## Inhalt

- [Für wen ist das?](#für-wen-ist-das)
- [Schnellstart](#schnellstart)
- [Die zwei Modi](#die-zwei-modi)
- [Themen & Aufgabentypen](#themen--aufgabentypen)
- [Die vier Simulationen](#die-vier-simulationen)
- [Bedienung auf dem iPad](#bedienung-auf-dem-ipad)
- [Technischer Aufbau](#technischer-aufbau)
- [Auf GitHub Pages veröffentlichen & aktualisieren](#auf-github-pages-veröffentlichen--aktualisieren)
- [Aufgaben anpassen oder ergänzen](#aufgaben-anpassen-oder-ergänzen)
- [Datenschutz](#datenschutz)
- [Lizenz & Credits](#lizenz--credits)

---

## Für wen ist das?

- **Schülerinnen und Schüler** der 8. Klasse zum Üben, Wiederholen und zur Prüfungsvorbereitung – mit **sofortiger Rückmeldung** zu jeder Aufgabe.
- **Lehrkräfte**, die eine sofort einsatzbereite, digitale Optik-Sammlung suchen – zum Projizieren, für Freiarbeit, Vertretungsstunden oder als Hausaufgabe über einen Link.

Behandelte Physik: Sehen & Licht, Reflexion & Spiegel, Brechung, Totalreflexion & Lichtleiter, Sammellinse (Bildkonstruktion, Linsengleichung), Auge & Fehlsichtigkeit – plus vermischte Transferaufgaben.

---

## Schnellstart

**Nichts zu installieren.** Es gibt drei Wege:

1. **Online (empfohlen):** Den GitHub-Pages-Link öffnen (siehe unten). Ideal, um ihn per QR-Code oder in der Lernplattform an die Klasse zu verteilen.
2. **Lokal:** Alle Dateien in **denselben Ordner** legen und `index.html` im Browser öffnen (Doppelklick bzw. „Öffnen mit → Safari/Chrome").
3. **Offline auf dem iPad:** Dateien z. B. in *iCloud Drive* oder *Dateien* ablegen und **in Safari** öffnen (nicht nur in der Vorschau – siehe [iPad-Hinweise](#bedienung-auf-dem-ipad)).

> **Wichtig:** Die fünf Dateien gehören zusammen in **einen Ordner**. Die Simulationen werden aus `index.html` über relative Pfade aufgerufen; fehlt eine Datei, öffnet die zugehörige Simulation nicht.

---

## Die zwei Modi

Beide werden vom Startbildschirm aus erreicht.

### 🎓 Lernmodus
- Sechs Themen als Lernkarten. Pro Thema zuerst eine **kompakte Zusammenfassung**, darunter die passenden **Übungsaufgaben**.
- **Sofortiges Feedback** nach jeder Antwort, inklusive Erklärung und – bei Fehlern – gezielten Hinweisen zur jeweils gewählten Fehlantwort.
- **Schwierigkeitsfilter** (alle / leicht / mittel / schwer) pro Thema.

### 🎯 Prüfungsmodus
- Selbst zusammengestellte „Prüfung": **Kapitel auswählen** und **Fragenzahl** wählen (5 / 10 / 15).
- Die Aufgaben werden **zufällig gezogen** und am Ende **ausgewertet** (Fortschrittsbalken, richtig/teilweise/falsch pro Frage, Ergebnistabelle).
- Reine Spiel-/Labyrinth-Aufgaben sind hier ausgenommen, damit die Prüfung fair bewertbar bleibt.

---

## Themen & Aufgabentypen

**Themen:** Sehen & Licht · Reflexion & Spiegel · Brechung · Totalreflexion & Lichtleiter · Sammellinse · Auge & Fehlsichtigkeit · Vermischte Aufgaben (Transfer).

Neben klassischen **Single- und Multiple-Choice-Fragen** gibt es zahlreiche **interaktive Aufgabentypen**, u. a.:

| Typ | Was die Schüler tun |
|-----|---------------------|
| `bildwahl` | Das richtige Bild/Ergebnis auswählen |
| `winkel` | Einen Winkel einstellen (z. B. Grenzwinkel der Totalreflexion) |
| `strahlengang` / `schirm` / `schirmjagd` | Strahlengänge und Bildentstehung an der Linse erkunden |
| `spiegelort` / `spiegelblick` / `spiegellabyrinth` | Reflexion und Spiegelbilder konstruieren |
| `peilung` / `vergleich` / `zuordnen` | Peilen, vergleichen, Begriffe zuordnen |
| `lupe` / `lupenauge` / `auge` | Lupe und Auge/Fehlsichtigkeit untersuchen |
| `fehlersuche` | Fehler in einer Aussage oder Skizze finden |
| `linsenbau` | Die 3D-Linsenwerkstatt (Aufgabe E12, siehe unten) |

Jede interaktive Aufgabe meldet ihren Fortschritt an die Aufgabenkarte zurück (Prüf-Button, Bewertung).

---

## Die vier Simulationen

Alle Simulationen sind **eigenständige Seiten**, die sich per Klick auf den jeweiligen Launcher-Button **in einem neuen Browser-Tab** öffnen. So bleibt die Aufgabenseite im Ausgangstab und verliert keinen Bildschirmplatz. Jede Simulation hat oben einen Button **„↩ Zurück zur Aufgabe"**, der den Tab wieder schließt.

| Datei | Simulation | Erscheint beim Thema |
|-------|-----------|----------------------|
| `sim_sammellinse.html` | **Sammellinse** – virtuelle optische Bank, Bildkonstruktion, Erkunden, Vorhersagen, „Jetzt du!" | Sammellinse |
| `sim_brechung.html` | **Brechung** – freier Experimentier-Aufbau + Vorhersagen | Brechung, Totalreflexion & Lichtleiter, Vermischte Aufgaben |
| `sim_totalreflexion.html` | **Taucherblick & Snellius-Fenster** – Totalreflexion, Grenzwinkel, scheinbare Sonne/Fisch | Totalreflexion & Lichtleiter |
| `sim_linsenbau.html` | **3D-Linsenwerkstatt** (Aufgabe E12) – Linsen schleifen in 3D (three.js), sechs Aufträge | Sammellinse (bzw. Start-Button der Aufgabe E12) |

**Besonderheit 3D-Linsenwerkstatt:** Sie meldet ihren Fortschritt und den Erfolg über eine Fenster-Verbindung an die Aufgabe zurück. Wer alle sechs Aufträge löst, bekommt die Aufgabe E12 automatisch als *gelöst* markiert – auch wenn die Werkstatt in einem eigenen Tab läuft.

---

## Bedienung auf dem iPad

Die Umgebung ist für iPads gebaut, ein paar Punkte helfen im Klassensatz:

- **In Safari öffnen, nicht nur in der Vorschau.** Öffnet man eine Datei aus *Dateien*/*iCloud* nur in der iPad-Schnellansicht, läuft kein JavaScript. Die Simulationen zeigen dann einen Hinweis: über **„Teilen → In Safari öffnen"** richtig starten. Am einfachsten ist ohnehin der **GitHub-Pages-Link**.
- **Pop-ups erlauben.** Die Simulationen öffnen sich als neuer Tab. Wird das blockiert, erscheint ein kurzer Hinweis „Bitte Pop-ups erlauben". In den meisten Fällen funktioniert das Antippen aber problemlos, weil es durch eine echte Fingertipp-Aktion ausgelöst wird.
- **Zurück zur Aufgabe:** Der Button oben in jeder Simulation schließt den Sim-Tab und bringt den Aufgaben-Tab wieder nach vorn.
- **Hell/Dunkel:** Über den Farbmodus-Schalter; die Wahl wird im Browser gemerkt.

---

## Technischer Aufbau

- **Reines HTML/CSS/JavaScript**, kein Build-Schritt, keine Abhängigkeiten aus dem Netz.
- **three.js** (für die 3D-Werkstatt) ist **direkt in `sim_linsenbau.html` eingebettet** – kein CDN, damit auch offline alles läuft.
- **Kein Backend, keine Datenbank.** Der Lern-Fortschritt lebt im Browser während der Sitzung; die Themen-/Farbwahl wird lokal gespeichert (`localStorage`). Es werden **keine Daten an einen Server gesendet**.
- Die Simulationen werden über **relative Pfade** geladen und laufen deshalb identisch offline (gleicher Ordner) wie auf GitHub Pages.

**Dateien:**

```
Optik/
├── index.html                 → Aufgabensammlung (Lern- & Prüfungsmodus) – das Startdokument
├── sim_sammellinse.html       → Simulation: Sammellinse
├── sim_brechung.html          → Simulation: Brechung
├── sim_totalreflexion.html    → Simulation: Taucherblick & Snellius-Fenster
├── sim_linsenbau.html         → 3D-Linsenwerkstatt (three.js eingebettet, ~1 MB)
└── README.md                  → diese Datei
```

---

## Auf GitHub Pages veröffentlichen & aktualisieren

Es ist eine reine statische Seite – an den **Pages-Einstellungen muss nichts geändert werden**.

**Erstveröffentlichung:**
1. Alle Dateien in ein GitHub-Repository legen (per Web-Upload „Add file → Upload files" oder per Git).
2. Im Repo unter **Settings → Pages** die Quelle auf den Branch (meist `main`, Ordner `/root`) stellen.
3. Nach kurzer Zeit ist die Seite unter `https://<benutzername>.github.io/<repo>/` erreichbar. Diesen Link verteilst du an die Klasse.

**Aktualisieren:** Einfach die geänderten Dateien neu hochladen (überschreiben) und committen – Pages baut automatisch neu (meist unter einer Minute).

> ⚠️ **Cache beachten:** Browser – besonders auf iPads – halten die alte Version teils hartnäckig fest. Nach einem Update ggf. **hart neu laden** (Tab schließen und neu öffnen bzw. Seite aktualisieren), sonst sieht man kurz noch den alten Stand.

---

## Aufgaben anpassen oder ergänzen

Alle Aufgaben stehen als JavaScript-Objekte in `index.html` (Suche im Quelltext nach `Block A:` … `Block G:`). Eine Aufgabe sieht z. B. so aus:

```js
{
 id: "D01",                               // eindeutige Kennung (Blockbuchstabe + Nummer)
 topic: "Totalreflexion & Lichtleiter",   // muss exakt einem der Themen entsprechen
 diff: 2,                                  // Schwierigkeit: 1 = leicht, 2 = mittel, 3 = schwer
 multi: true,                              // true = mehrere richtige Antworten (Kästchen)
 q: "Unter welchen Bedingungen …?",        // Fragetext (HTML erlaubt)
 options: [ "Aussage 1", "Aussage 2", … ],
 correct: [0, 1, 3],                       // Indizes der richtigen Optionen
 expl: "Beide Bedingungen müssen …",       // Erklärung nach dem Antworten
 misc: { "2": "Warum Option 2 falsch ist …" }  // optionale Hinweise pro Fehlantwort
}
```

Interaktive Aufgaben tragen statt `multi` ein `type` (z. B. `"winkel"`) und einen `inter`-Block mit den Startwerten der Simulation.

**Tipps:**
- Neue Aufgabe am einfachsten aus einer bestehenden desselben Typs **kopieren und anpassen**.
- Die **`id` muss eindeutig** sein und das `topic` **exakt** wie in der Themenliste geschrieben.
- Nach dem Bearbeiten die Seite im Browser öffnen und die neue Aufgabe im passenden Thema kontrollieren.

Da alles in einer Datei steht, empfiehlt sich vor größeren Änderungen eine **Sicherungskopie** von `index.html`.

---

## Datenschutz

Für den schulischen Einsatz relevant: Die Sammlung ist **vollständig lokal**. Es gibt **keine Konten, kein Tracking, keine Cookies zu Werbezwecken und keine Übertragung von Schülerdaten**. Fortschritt und Einstellungen bleiben im Browser des jeweiligen Geräts.

---

## Lizenz & Credits

- **Inhalte** (Aufgaben, Simulationen, Texte): für den Unterrichtsgebrauch erstellt. Lege hier bei Bedarf deine gewünschte Lizenz fest (z. B. CC BY-SA für freie Weitergabe).
- **three.js** (in `sim_linsenbau.html`): © Three.js Authors, MIT-Lizenz.

---

*Physik 8. Klasse · Teilgebiet Optik · Lern- und Prüfungsumgebung.*
