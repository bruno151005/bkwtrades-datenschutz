# Datenschutzerklärung — bkwtrades Instagram-Automatik

Zwei statische Seiten, die als **Privacy Policy URL** in der Meta-App-Review verlangt
werden. Kein Build, kein Framework — GitHub Pages liefert sie direkt aus.

```
index.html   deutsche Fassung (maßgeblich)
en.html      englische Fassung — die Meta-Reviewer lesen Englisch
```

## Vor der Veröffentlichung ausfüllen

In **beiden** Dateien stehen Platzhalter für die Anschrift:

* `[STRASSE UND HAUSNUMMER]` / `[STREET AND NUMBER]`
* `[PLZ]` / `[POSTCODE]`

Art. 13 DSGVO verlangt Identität und Kontaktdaten des Verantwortlichen. Anders als auf
Angeboten lässt sich die Straße hier nicht weglassen.

## Inhaltlicher Abgleich mit dem Bot

Die Tabelle „Welche Daten gespeichert werden" bildet ab, was `insta-dm-bot` tatsächlich
schreibt (`store.contacts`, `crm.events`): IGSID, Benutzername, Codewort/Flow, Media-ID,
Nachrichtentext, Zeitstempel, Stufe, Follower-Status. **Ändert sich das Datenmodell,
ändert sich diese Seite mit** — sonst behauptet die Erklärung etwas Falsches.

Der Löschweg ist bewusst eine Handaktion: Zeile in `contacts` und alle `events` zur
`igsid` entfernen.

## Veröffentlichen

Repo auf GitHub anlegen (öffentlich), beide Dateien hochladen, dann
**Settings → Pages → Source: „Deploy from a branch" → Branch `main`, Ordner `/ (root)`**.

Nach ein paar Minuten erreichbar unter:

```
https://<benutzername>.github.io/<repo-name>/
```

Diese URL kommt im Meta-App-Dashboard unter **Einstellungen → Allgemein →
URL der Datenschutzrichtlinie** hinein.
