# 🏡 Effingen Entscheidungs-Wizard

Interaktive Entscheidungshilfe für die 4-Familien-Konstellation in Effingen — soll Effingen jetzt gekauft werden oder ist Warten sinnvoller?

## 🎯 Worum geht's

Vier Familien stehen vor einer gemeinsamen Kaufentscheidung in Effingen (Böztal, Aargau). Dieser Wizard hilft jeder Familie individuell, eine **objektive und transparente Einschätzung** zur Effingen-Chance zu treffen — und macht die Faktoren sichtbar, die in die Entscheidung einfliessen.

Jede Familie füllt den Wizard für sich aus, bekommt eine begründete Empfehlung und kann das Resultat als PDF speichern.

## 🚀 So nutzt ihr das Tool

1. Öffnet den Link im Browser
2. Tragt euren Familiennamen ein
3. Beantwortet die 6 Fragen ehrlich (Klick auf das **i** zeigt Erklärungen)
4. Klickt auf **"Empfehlung berechnen"**
5. Schaut euch die Empfehlung, die Begründung und die Sensitivitätsanalyse an
6. Speichert das Resultat als PDF (Button am Ende)
7. Schickt das PDF an die anderen Familien zum Vergleich

## 📊 Die 6 Bewertungs-Kriterien

| # | Kriterium | Was bewertet wird |
|---|---|---|
| 1 | **Effingen-Objekt-Qualität** | Wie gut passt das konkrete Objekt? |
| 2 | **Standort Effingen** | Wie tragbar ist Effingen langfristig? (5 Sub-Kriterien optional) |
| 3 | **Konstellations-Abhängigkeit + Investment** | Wie wichtig ist die 4-Parteien-Konstellation? Wohnen oder Investition? |
| 4 | **Optimierung vs. Sicherheit** | Was ist euch wichtiger: das beste Objekt oder Klarheit jetzt? |
| 5 | **Markteinschätzung + Konstellations-Risiko** | Wie sieht der Markt aus? Wie hoch ist das Risiko, dass die Konstellation bricht? |
| 6 | **Verfügbare Zeit** | Wie lange könnt ihr realistisch warten? |

## 🧮 Wie die Empfehlung entsteht

Das Tool berechnet zwei unabhängige Scores:

- **Score "Kaufen jetzt"** = Mittel aus Objekt + Standort + (Konstellation/Investment-Mix)
- **Score "Warten"** = Marktscore × (1 − Risiko-Anteil) + Worst-Case × Risiko-Anteil, mit Zeit-Modifier (±21%)

Die finale Empfehlung wird durch eure **Optimierung-vs-Sicherheits-Präferenz** gewichtet.

→ Methodisch wurde besonders darauf geachtet, alle systematischen Verzerrungen zu eliminieren: relative Score-Annahmen statt fixer Werte, symmetrische Skalen, gewichtete Sub-Kriterien, ausgewogene Zeit-Wirkung.

---

## 📦 Deployment auf GitHub Pages

### Schritt 1: GitHub-Repository erstellen

1. Gehe auf [github.com](https://github.com) und logge dich ein
2. Klick auf **"+"** oben rechts → **"New repository"**
3. Repository-Name: `effingen-wizard` (oder ähnlich)
4. Sichtbarkeit: **Public** (wichtig für GitHub Pages auf kostenlosem Account)
5. Haken setzen bei **"Add a README file"** (wir überschreiben sie später)
6. Klick **"Create repository"**

### Schritt 2: Dateien hochladen

1. Im neuen Repository: Klick **"Add file"** → **"Upload files"**
2. Ziehe `index.html` und `README.md` ins Browser-Fenster
3. Commit-Message: `Initial deployment`
4. Klick **"Commit changes"**

### Schritt 3: GitHub Pages aktivieren

1. Im Repository: Klick auf **"Settings"** (oben rechts)
2. Linkes Menü: Klick auf **"Pages"**
3. Unter **"Build and deployment"**:
   - **Source:** "Deploy from a branch"
   - **Branch:** `main` / Folder: `/ (root)`
4. Klick **"Save"**
5. Warte 1-2 Minuten

### Schritt 4: Link teilen

GitHub zeigt dir nach kurzer Zeit oben auf der Pages-Seite den Link an, in der Form:

```
https://DEIN-GITHUB-NAME.github.io/effingen-wizard/
```

Diesen Link kannst du an die 4 Familien schicken. Sie öffnen ihn im Browser, füllen ihn aus und exportieren ihr Resultat als PDF.

## 🔧 Anpassungen / Updates

Wenn du Änderungen an `index.html` machen willst:

1. Im Repository auf `index.html` klicken
2. Auf das **Bleistift-Symbol** (Edit) klicken
3. Änderungen vornehmen
4. **"Commit changes"** unten
5. Nach 1-2 Minuten ist die neue Version online

## 🛡️ Datenschutz

- **Keine Daten verlassen den Browser:** Alle Eingaben werden lokal verarbeitet, nichts wird gespeichert oder hochgeladen
- **Keine Cookies, kein Tracking, keine Analytics**
- **Kein Backend:** Reine HTML-Datei, läuft offline
- **PDF-Export** geschieht via Browser-Druckfunktion lokal auf dem Gerät

## 📝 Lizenz

Dieses Tool wurde für den persönlichen Gebrauch der 4 Familien erstellt. Anpassung und Weiternutzung gerne — ohne Gewähr.

---

**Erstellt mit Claude (Anthropic) · Frühjahr 2026**
