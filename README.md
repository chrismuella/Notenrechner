# Notenrechner

Eine einfache, statische HTML-Anwendung zur Berechnung deines Durchschnitts aus Vornote und Abschlussarbeit bzw. zur Ermittlung der benötigten Abschlussnote.

---

## Features

* **Standardverfahren**: Berechnung des genauen (3 Nachkommastellen) und gerundeten Gesamtdurchschnitts aus Vornote und Abschlussarbeit.
* **Alternatives Verfahren**: Tabelle mit allen Zeugniszielen (1–6) und den dazugehörigen benötigten Noten in der Abschlussarbeit (als Bereich oder Einzelwert).
* **Responsives Design**: CSS Grid passt Layout ab 320 px automatisch an.
* **Benutzerfreundliche Controls**: Dezimal-Inputs mit step=0.01, Validierung und Fokushervorhebung.
* **Modernes Styling**: Abgerundete Ecken, sanfte Schatten, Hover- und Fokus-Animationen.

---

## Installation

1. Repository klonen oder Dateien herunterladen:

   ```bash
   git clone https://github.com/<dein-user>/notenrechner.git
   cd notenrechner
   ```
2. Die Datei `index.html` im Browser öffnen:

   * Doppelklick auf die Datei
   * Oder über `http://localhost` (bei lokalem Server)

---

## Nutzung

1. **Berechnung mit Abschlussarbeit**:

   * Gib deine Vornote (z. B. 2,85) und die Note der Abschlussarbeit (1–6) ein.
   * Klicke auf **Berechnen**.
   * Du erhältst den genauen Durchschnitt, die gerundete Zeugnisnote und die benötigte Note für Zeugnisnote 5.

2. **Nur Vornote**:

   * Gib deine Vornote ein.
   * Klicke auf **Optionen berechnen**.
   * Es erscheint eine Tabelle: Für jede Zielnote (1–6) siehst du, welche Abschlussnote du minimal bzw. maximal benötigst.

---

## Deployment

### 1. GitHub Pages

1. Neues Repository auf GitHub anlegen und Code pushen.
2. In den **Settings → Pages** den Branch (`main`/`gh-pages`) und den Ordner `/ (root)` auswählen.
3. Deine Seite ist in Kürze unter:

   ```
   https://<username>.github.io/<repo-name>/
   ```

### 2. Netlify

1. Netlify-Account erstellen.
2. Entweder per **Drag & Drop** deinen Ordner hochladen oder Git-Repo verbinden.
3. Automatisches Deployment bei jedem Push.

### 3. Vercel

1. Vercel-Account anlegen und GitHub verbinden.
2. Projekt importieren (erkennt statische Seite automatisch).
3. Live-URL erhalten.

---

## Anpassungen

* **Steuer-Elemente**: Maximalbreite der Inputs/Buttons über `--control-width` in der CSS-Variable ändern.
* **Farben**: Primär- und Hintergrundfarben in den CSS-Variablen definieren.
* **Schriftgrößen und Abstände**: Passe die rem-basierten Variablen `--font-size-*` und `--gap` an.

---

## Lizenz

MIT © Christoph Müller
