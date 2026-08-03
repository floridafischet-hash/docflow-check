# Dokumenten-Workflow-Check

Kostenloser Nachfrage-Test für ein produktisiertes B2B-Angebot rund um Paperless-ngx, OCR und strukturierte Dokumentenablage.

## Ziel
- legale, kostenlose Nachfrageprüfung
- keine serverseitige Formularspeicherung
- Kontaktaufnahme über Telegram-Bot als bewusster Nutzer-Schritt

## Dateien
- `index.html` – öffentliche Landingpage

## CTA-Mechanik
1. Besucher füllt das Formular aus.
2. Seite erzeugt die Zusammenfassung lokal im Browser.
3. Besucher kopiert den Text.
4. Besucher öffnet `@FloriHermesbot` mit Start-Parameter `docflow-check`.
5. Besucher sendet die Zusammenfassung manuell im Bot.

## Warum diese Variante
- kostenlos
- kein zusätzliches Backend
- datensparsam
- schnell testbar

## Nächste sinnvolle Schritte
- öffentlich deployen (GitHub Pages)
- in 1–2 kostenlosen Kanälen posten
- Rückmeldungen zählen: Klicks, Bot-Starts, echte Anfragen
