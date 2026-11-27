# Proovy – Prototyp

Klickbarer Prototyp von Proovy (HackWG, Team 9): Studi-App, Anbieter-Ansicht und Lenas öffentlicher Skill-Pass. Alles läuft im Browser, ohne Server und ohne Login. Alle Daten sind Demo-Daten.

## Aufbau

- `index.html` – die ganze App
- `pass/lena-becker/index.html` – dieselbe Datei; unter dieser Adresse zeigt sie Lenas öffentlichen Skill-Pass

## Adressen mit GitHub Pages

- App: `https://<github-name>.github.io/<repo-name>/`
- Skill-Pass: `https://<github-name>.github.io/<repo-name>/pass/lena-becker/`

Den Link zum Skill-Pass baut die App selbst aus ihrer Adresse. „Teilen“ im Skill-Pass zeigt also immer den passenden Link.

## Gut zu wissen

- Der Demo-Zustand liegt im Browser jeder Person, die die Seite öffnet. „Demo zurücksetzen“ stellt den Anfang wieder her.
- Wer den Skill-Pass öffnet, ohne vorher die Demo gemacht zu haben, sieht zwei Beispiel-Einträge.

## Aktualisieren

Beide `index.html` müssen gleich sein: Neue Version an beiden Stellen hochladen. GitHub Pages braucht danach bis zu 10 Minuten.

Eine neue Version aus Claude funktioniert nur dann unter `/pass/lena-becker/`, wenn sie den Abschnitt „Öffentlicher Skill-Pass“ im Script enthält. Am einfachsten lasst ihr neue Versionen von Claude für GitHub Pages vorbereiten.
