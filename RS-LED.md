# RS-LED Sitzungsprotokoll

Diese Datei ist das fortlaufende technische Sitzungs- und Uebergabeprotokoll fuer OpenCode. Sie muss in jeder Sitzung gelesen, mit dem tatsaechlichen Repository-, Twenty- und Mail-Stand abgeglichen und aktualisiert werden. Twenty bleibt die verbindliche Quelle fuer CRM-Daten und die Wissensbasis.

## Aktueller Arbeitsstand

- Datum: 06.08.2026
- Lead Stephan Rzepka wurde technisch geprueft und in Twenty auf Screening gesetzt.
- Die Erstkontakt-Mail wurde intern an Georg zur Pruefung gegeben.
- Der Versand an `g.schroejahr@rs-led.de` wurde im Gesendet-Ordner verifiziert: 05.08.2026, 23:52:57 Uhr MESZ, Nachrichten-ID `reaaaaej`, Thread-ID `ej`.
- Georgs Aenderungsantwort zur Rzepka-Pruefmail wurde verifiziert: 06.08.2026, 09:02:45 Uhr MESZ, Nachrichten-ID `riaaaaek`. Seine drei Hinweise wurden eingearbeitet: Konfiguratorabstand als Durchschnittswert behandeln, keine Schriftgroesse abfragen und keine Lesbarkeit durch Glas abfragen.
- Die korrigierte Rzepka-Fassung liegt als gepruefter Kundenentwurf vor: an `stephan.rzepka@t-online.de`, Georg Schroejahr unter `g.schroejahr@rs-led.de` in BCC, Betreff `Rückfragen zu Ihrer Indoor-LED-Anzeige`, Draft-ID `siaaaaes`, Thread-ID `es`, nicht versendet. Twenty wurde auf den Kundenentwurfs- und Versandstatus aktualisiert.
- Der Nutzer bestaetigte am 06.08.2026 den manuellen Versand der Rzepka-Kundenmail. Die technische Nachkontrolle fand jedoch keinen Treffer im Gesendet-Ordner; Entwurf `siaaaaes` liegt weiterhin mit `$draft` im Entwurfsordner. Die Bestaetigung ist in Twenty dokumentiert, der tatsaechliche Kundenversand bleibt technisch unverifiziert und wird nicht als versendet gefuehrt.
- Die korrigierte interne Pruefmail an Georg wurde dagegen im Gesendet-Ordner verifiziert: 06.08.2026, 09:38:54 Uhr MESZ, Betreff `Korrigiert zur Prüfung: Erstkontakt Stephan Rzepka`, Nachrichten-ID `r2aaaaep`, Thread-ID `ep`.
- Der Erstkontakt-Skill behandelt den Konfiguratorabstand nun als durchschnittlichen Betrachtungsabstand und verbietet routinemaessige Rueckfragen dazu, Fragen nach einer kleinsten beziehungsweise gewuenschten Schriftgroesse sowie Fragen nach Aussenlesbarkeit durch Glas oder Scheibenart.
- Die neuen Konfiguratorregeln wurden mit Commit `47a45b4` festgehalten.
- Fuer Dennis Wack wurde die Nachricht von Georg `Ihr Angebot 2026-TS01 - LED-Anzeigetafel für den TSV Großen-Linden` als gepruefter Kundenentwurf weitergeleitet: an `denyo611@googlemail.com`, Georg Schröjahr unter `g.schroejahr@rs-led.de` in BCC, Draft-ID `rqaaaaem`, Thread-ID `em`.
- Der Entwurf enthaelt vier PDF-Anhaenge: `Angebot-2026-TS01.pdf`, `Spec-Sheet-ARENA-Serie.pdf`, `Kleines-LED-Lexikon.pdf` und `AGB-rs-led.pdf`. Das Rendering-Bild wurde gemaess Mailvorgabe nicht angehaengt. Der Entwurf ist nicht versendet.
- Der zuvor ohne Georg in BCC angelegte Entwurf `rmaaaael` wurde in den Papierkorb verschoben. Opportunity und Versandaufgabe zum TSV Großen-Linden wurden in Twenty auf den aktuellen Entwurfs- und Versandstatus aktualisiert.
- Die Skill-Regel zur internen Rasterpruefung wurde mit Commit `a45e6f4` festgehalten.
- Die Nachverfolgung interner Pruefmails an Georg wurde mit Commit `6f6030d` im Erstkontakt-Skill festgehalten.
- `AGENTS.md` schreibt nun die Pflege dieses Sitzungsprotokolls in jeder Sitzung verbindlich vor.

## Offene Punkte

1. Nutzer fragen, ob der Entwurf an Dennis Wack im Postfach versendet wurde. Erst nach Bestaetigung den Gesendet-Ordner nach Empfaenger und Betreff pruefen und den Versandstatus in Twenty aktualisieren.
2. Kundenentwurf `Rückfragen zu Ihrer Indoor-LED-Anzeige` an Stephan Rzepka im Postfach senden und den Gesendet-Ordner danach erneut verifizieren. Bis zu einem Treffer den Versand nicht als erledigt fuehren.

## Pflegevorgabe

- Nur verifizierte Tatsachen als erledigt dokumentieren.
- Entwurf, Versand, Antwort und Freigabe klar voneinander trennen.
- Nach wesentlichen Aenderungen den aktuellen Stand, offene Punkte und naechsten Schritt aktualisieren.
- Commits mit Kurzbeschreibung und Commit-ID festhalten.
- Keine parallele CRM- oder Wissensbasis aufbauen; Detaildaten gehoeren nach Twenty.
