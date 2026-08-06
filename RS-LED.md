# RS-LED Sitzungsprotokoll

Diese Datei ist das fortlaufende technische Sitzungs- und Uebergabeprotokoll fuer OpenCode. Sie muss in jeder Sitzung gelesen, mit dem tatsaechlichen Repository-, Twenty- und Mail-Stand abgeglichen und aktualisiert werden. Twenty bleibt die verbindliche Quelle fuer CRM-Daten und die Wissensbasis.

## Aktueller Arbeitsstand

- Datum: 06.08.2026
- Lead Stephan Rzepka wurde technisch geprueft und in Twenty auf Screening gesetzt.
- Die Erstkontakt-Mail wurde intern an Georg zur Pruefung gegeben.
- Der Versand an `g.schroejahr@rs-led.de` wurde im Gesendet-Ordner verifiziert: 05.08.2026, 23:52:57 Uhr MESZ, Nachrichten-ID `reaaaaej`, Thread-ID `ej`.
- Georgs Aenderungsantwort zur Rzepka-Pruefmail wurde verifiziert: 06.08.2026, 09:02:45 Uhr MESZ, Nachrichten-ID `riaaaaek`. Seine drei Hinweise wurden eingearbeitet: Konfiguratorabstand als Durchschnittswert behandeln, keine Schriftgroesse abfragen und keine Lesbarkeit durch Glas abfragen.
- Die korrigierte Rzepka-Kundenmail wurde im Gesendet-Ordner verifiziert: 06.08.2026, 09:52:51 Uhr MESZ, an `stephan.rzepka@t-online.de`, Georg Schroejahr unter `g.schroejahr@rs-led.de` in BCC, Betreff `Rückfragen zu Ihrer Indoor-LED-Anzeige`, Nachrichten-ID `suaaaaev`, Thread-ID `ev`, keine Anhaenge.
- Die korrigierte interne Pruefmail an Georg wurde dagegen im Gesendet-Ordner verifiziert: 06.08.2026, 09:38:54 Uhr MESZ, Betreff `Korrigiert zur Prüfung: Erstkontakt Stephan Rzepka`, Nachrichten-ID `r2aaaaep`, Thread-ID `ep`.
- Der Erstkontakt-Skill behandelt den Konfiguratorabstand nun als durchschnittlichen Betrachtungsabstand und verbietet routinemaessige Rueckfragen dazu, Fragen nach einer kleinsten beziehungsweise gewuenschten Schriftgroesse sowie Fragen nach Aussenlesbarkeit durch Glas oder Scheibenart.
- Die neuen Konfiguratorregeln wurden mit Commit `47a45b4` festgehalten.
- Das Angebot 2026-TS01 an Dennis Wack wurde im Gesendet-Ordner verifiziert: 06.08.2026, 09:27:56 Uhr MESZ, an `denyo611@googlemail.com`, Georg Schroejahr unter `g.schroejahr@rs-led.de` in BCC, Betreff `WG: Ihr Angebot 2026-TS01 - LED-Anzeigetafel für den TSV Großen-Linden`, Nachrichten-ID `ruaaaaen`, Thread-ID `en`.
- Die Wack-Mail enthaelt vier PDF-Anhaenge: `Angebot-2026-TS01.pdf`, `Spec-Sheet-ARENA-Serie.pdf`, `Kleines-LED-Lexikon.pdf` und `AGB-rs-led.pdf`. Das Rendering-Bild wurde gemaess Mailvorgabe nicht angehaengt.
- Aus den Fehlern dieser Weiterleitung wurde eine verbindliche Regel abgeleitet und in `AGENTS.md` sowie der Twenty-Wissensbasis `Style & Guides` festgehalten: Bei einem reinen Weiterleitungsauftrag keinen Einleitungstext, keine zusaetzliche Anrede und keinen Trenner wie `Weitergeleitete Nachricht` einfuegen; alle Originalanhaenge einschliesslich PNG/JPG uebernehmen; fremde oder doppelte Footer entfernen; der fertige Entwurf darf genau einen Footer des sendenden Kontos enthalten.
- Fuer den fehlenden Rendering-Anhang der Wack-Mail wurde zunaechst nur ein interner Nachtragsentwurf an Georg angelegt: Betreff `Zur Ansicht: Nachtrag Rendering an Dennis Wack`, Draft-ID `tyaaaae1`, Thread-ID `e1`, keine Anhaenge, nicht versendet. Ein zuvor vorzeitig angelegter Kundenentwurf wurde in den Papierkorb verschoben. Twenty wurde auf `Georgs Pruefung abwarten` aktualisiert.
- Der zuvor ohne Georg in BCC angelegte Entwurf `rmaaaael` wurde in den Papierkorb verschoben. Opportunity und Versandaufgabe zum TSV Großen-Linden wurden in Twenty auf den aktuellen Entwurfs- und Versandstatus aktualisiert.
- Die Skill-Regel zur internen Rasterpruefung wurde mit Commit `a45e6f4` festgehalten.
- Die Nachverfolgung interner Pruefmails an Georg wurde mit Commit `6f6030d` im Erstkontakt-Skill festgehalten.
- `AGENTS.md` schreibt nun die Pflege dieses Sitzungsprotokolls in jeder Sitzung verbindlich vor.

## Offene Punkte

1. Kundenantwort von Stephan Rzepka abwarten; bei ausbleibender Antwort am 13.08.2026 nachfassen.
2. Internen Nachtragsentwurf `Zur Ansicht: Nachtrag Rendering an Dennis Wack` an Georg senden und seine Freigabe abwarten. Erst danach den Kundennachtrag an Dennis Wack anlegen; das Rendering-Bild fuegt der Nutzer im Mailprogramm hinzu.

## Pflegevorgabe

- Nur verifizierte Tatsachen als erledigt dokumentieren.
- Entwurf, Versand, Antwort und Freigabe klar voneinander trennen.
- Nach wesentlichen Aenderungen den aktuellen Stand, offene Punkte und naechsten Schritt aktualisieren.
- Commits mit Kurzbeschreibung und Commit-ID festhalten.
- Keine parallele CRM- oder Wissensbasis aufbauen; Detaildaten gehoeren nach Twenty.
