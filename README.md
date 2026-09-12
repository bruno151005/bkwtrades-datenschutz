# Datenschutzerklärung — bkwtrades Instagram-Automatik

Zwei statische Seiten, die als **Privacy Policy URL** in der Meta-App-Review verlangt
werden. Kein Build, kein Framework — GitHub Pages liefert sie direkt aus.

```
index.html   deutsche Fassung (maßgeblich)
en.html      englische Fassung — die Meta-Reviewer lesen Englisch
```

## Anschrift — ✅ eingetragen am 12.09.2026

Beide Dateien tragen jetzt die vollständige Anschrift des Verantwortlichen
(Bruno Westphal, Ebertstraße 22b, 07743 Jena). Art. 13 DSGVO verlangt Identität und
Kontaktdaten — anders als auf Angeboten lässt sich die Straße hier nicht weglassen.

> ⚠️ **Damit steht die Wohnanschrift öffentlich und indexierbar im Netz.** Sobald es ein
> Gewerbe mit eigener Geschäftsadresse gibt, hier ersetzen.

## Noch offen: Impressum

Die Datenschutzerklärung ist **nicht** das Impressum. Sobald das Instagram-Angebot
geschäftsmäßig ist (Giveaway → Discord → Angebot), greift zusätzlich die
Impressumspflicht nach § 5 DDG — ein eigenes Dokument, andere Pflichtangaben.
Kein Anwaltsrat, nur der Hinweis, dass es zwei Dinge sind.

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
