# Ein mal Eins

Eine Rechen-Lernapp für Kinder. Drei drehbare Walzen (Zahl · Rechenart · Zahl) stellen die Aufgabe, das Kind tippt das Ergebnis ein. Bei einer richtigen Antwort fliegen Sterne, bei einer falschen radiert ein Radiergummi die Zahl weg.

Die App ist eine einzige Datei: `index.html`. Daneben liegt die Benutzerdokumentation als PDF. Sie braucht keinen Server, keine Installation und kein Build.

## Funktionen

- **Vier Stufen**
  - Entdecker: + −
  - Forscher: + − ×
  - Profi: + − × :
  - Professor: Wurzelziehen (bis 2500)
- Walzen von Hand drehen oder per Knopf «Neue Aufgabe drehen»
- Geteilt- und Wurzelaufgaben gehen immer auf (die Walzen zeigen nur passende Zahlen)
- Optional eine **3. Zahlenwalze** mit Punkt vor Strich, z. B. 4 + 3 × 2
- **Rechenhilfe** mit gelbem Bogen unter dem Teil, der zuerst gerechnet wird
- Sternenzähler, der bei jedem Öffnen der App bei 0 beginnt

## Einstellungen für die Lehrperson

Über das Zahnrad oben rechts. Das Startpasswort ist **`Admin`**. Bitte nach dem ersten Öffnen ändern.

Einstellbar sind:

- welche Stufen sichtbar sind
- die grösste Zahl pro Stufe
- ob die Walzen von Hand gedreht werden dürfen
- 3. Zahlenwalze an/aus
- Rechenhilfe an/aus
- Sterne zurücksetzen
- Passwort ändern

In den Einstellungen öffnet **Benutzerdokumentation öffnen** die Anleitung `Ein_mal_Eins_Benutzerdokumentation.pdf`. Die PDF-Datei muss deshalb im selben Ordner liegen wie `index.html`.

Die Einstellungen werden im Browser des jeweiligen Geräts gespeichert (`localStorage`). Sie gelten also nur auf dem Gerät, auf dem sie gemacht wurden. Der Passwortschutz hält Kinder fern, ist aber keine echte Sicherheit.

## Starten

- **Lokal:** `index.html` im Browser öffnen.
- **GitHub Pages:**
  1. Repository erstellen und `index.html` sowie `Ein_mal_Eins_Benutzerdokumentation.pdf` hochladen.
  2. *Settings → Pages* öffnen.
  3. Unter *Source* «Deploy from a branch» wählen, Branch `main`, Ordner `/ (root)`, und speichern.
  4. Nach ein bis zwei Minuten ist die App unter `https://<benutzername>.github.io/<repository>/` erreichbar.

Die Schriften werden von Google Fonts geladen. Ohne Internet nimmt die App Ersatzschriften und funktioniert trotzdem.

## Copyright

© 2026 Mike Staub. Alle Rechte vorbehalten. Siehe [LICENSE](LICENSE).
