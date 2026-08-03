# Arbeitsfortsetzung in neuen Sitzungen

Wenn eine neue OpenCode-Sitzung in diesem Verzeichnis beginnt oder der Nutzer ohne weiteren Kontext sinngemäß „weiter“ sagt, frage nicht zuerst, womit du weitermachen sollst.

Prüfe stattdessen selbstständig den aktuellen Arbeitsstand im Repository, insbesondere:

- `git status`, vorhandene Diffs und die letzten Commits,
- Planungs-, Aufgaben- und Statusdateien,
- noch nicht abgeschlossene oder nicht verifizierte Änderungen,
- relevante Projekt- und Entwicklerdokumentation.

Leite daraus den zuletzt bearbeiteten Arbeitskontext und den sinnvollsten nächsten Schritt ab. Berichte dem Nutzer kurz, was du gefunden hast, und setze die Arbeit anschließend fort, sofern der nächste Schritt eindeutig und sicher ist.

Stelle erst dann eine gezielte Rückfrage, wenn die Prüfung keine belastbare Fortsetzung ermöglicht, mehrere wesentlich unterschiedliche Arbeitsrichtungen offen sind oder eine riskante beziehungsweise irreversible Entscheidung erforderlich wäre. Verwirf oder überschreibe niemals vorhandene Änderungen, nur um einen vermeintlich sauberen Ausgangszustand herzustellen.

## Outline-Dokumentation

Nur fuer dieses Projekt `/home/chris/web/rs-led` und seine Unterverzeichnisse gilt die Pflicht, bei relevanten Aenderungen, Neuinstallationen, Erkenntnissen oder Caveats die zugehoerige Outline-Dokumentation gemaess Convention-Dokument `TOsEetTSdj` zu pflegen. Diese Regel darf nicht auf andere Projekte unter `/home/chris/web` uebertragen werden.

## Erstkontakt bei Sportplatz-Leads

Bei vergleichbaren Sportplatz-Anzeigen sind etwa 30 m Betrachtungsabstand fuer grosse Spielstaende, Uhr, Vereinswappen und grossflaechige Sponsorenmotive plausibel. Diesen Abstand nicht routinemaessig erneut hinterfragen, sofern Groesse, Inhalt oder Standortgeometrie keinen Widerspruch erkennen lassen.

Sportplatz-Anzeigen standardmaessig einseitig planen. Nur nach einer beidseitigen oder mehrseitigen Ausfuehrung fragen, wenn Anfrage, Bilder oder Standort dies konkret nahelegen. Eine ausdruecklich angegebene Unterkante als Unterkante uebernehmen und nicht ohne Widerspruch in eine Rueckfrage zur Gesamthoehe umdeuten.

Massangaben aus dem LED-Konfigurator bezeichnen immer die sichtbare LED-Flaeche. Eine gewuenschte Blende kommt hinzu und vergroessert das spaetere Aussenmass. Nie mehr fragen, ob sich das angegebene Mass auf die LED-Flaeche oder das Aussenmass inklusive Blende bezieht.

Beim Erstkontakt stattdessen klaeren, an wen das Angebot gerichtet werden darf, und die Montageadresse abfragen, sofern diese Angaben noch fehlen.

## Erstkontakt bei haengender oder abgehaengter Montage

Wenn der Kunde im LED-Konfigurator ausdruecklich `haengend/abgehaengt` ausgewaehlt hat, diese Montageart als beantwortet behandeln. Nicht ohne konkreten Widerspruch erneut fragen, ob die LED-Wand dauerhaft haengen oder fuer Veranstaltungen auf- und abgebaut werden soll.

Bei dieser Montageart keine Unterkonstruktion abfragen, ankündigen oder einplanen. Stattdessen klaeren, an welchen vorhandenen Aufhaenge- beziehungsweise Befestigungspunkten die abgehaengte LED-Wand befestigt werden soll. Erforderliche kabinettspezifische Hanging Bars, Anschlagmittel und Sekundaersicherung sind Komponenten der Haengung und nicht als Unterkonstruktion zu bezeichnen.

## E-Mail-Versand

Beim angebundenen Mailkonto ist `can_send: false` der beabsichtigte Normalzustand und weder ein Fehler noch ein zu behebender Blocker. OpenCode soll E-Mails als vollstaendige, gepruefte und sendefertige Entwuerfe im Postfach anlegen. Wenn der Nutzer sinngemaess zum Senden auffordert, ist damit in diesem technischen Rahmen das Erstellen beziehungsweise Aktualisieren eines solchen Entwurfs gemeint; niemals einen tatsaechlichen Versand vortaeuschen.

Keine Bilder selbst in E-Mail-Entwuerfe einbetten oder als Anhang hinzufuegen. Der Nutzer fuegt Bilder im Mailprogramm eigenstaendig hinzu. Einen gewuenschten Hinweis auf Bilder im Mailtext darf OpenCode formulieren, die Bilddateien selbst aber nicht anfassen. Andere Anhaenge nur auf ausdruecklichen Auftrag hinzufuegen.

Wenn der Nutzer bei einem E-Mail-Auftrag ohne weitere Adressangabe `Georg` als Empfaenger nennt, ist damit immer `g.schroejahr@rs-led.de` gemeint. Eine abweichende Adresse nur verwenden, wenn der Nutzer sie ausdruecklich nennt.

Den Nutzer nach Abschluss einmal knapp und eindeutig ueber `Entwurf angelegt` beziehungsweise `nicht versendet` informieren. `can_send: false` nicht bei jedem Zwischenschritt erneut erklaeren, nicht wiederholt als Problem hervorheben und nicht staendig dieselbe manuelle Versandaufforderung wiederholen. Nur erneut darauf eingehen, wenn der Nutzer nach dem tatsaechlichen Versandstatus fragt, ein vermeintlicher Versand verifiziert werden muss oder sich die Mail-Faehigkeiten des Kontos geaendert haben.

Wenn der Nutzer ausdruecklich anweist, eine Mail an den anfragenden Kunden rauszuschicken, nach dem Anlegen oder Aktualisieren des geprueften Kundenentwurfs genau einmal fragen, ob er die Mail im Postfach versendet hat. Diese einmalige Versandnachfrage ist beabsichtigt und keine erneute Erklaerung von `can_send: false`. Eine Versandfreigabe oder ein Entwurf allein darf niemals als tatsaechlicher Versand dokumentiert werden.

Nach der Versandbestaetigung den Gesendet-Ordner nach Empfaenger und Betreff pruefen. Bei erfolgreicher Verifizierung den zugehoerigen Outline-Kundenvorgang und den Interessenten-Index auf `versendet` beziehungsweise `Versandauftrag erledigt` aktualisieren, Versandzeit und Nachrichten-ID dokumentieren, veraltete Entwurfsangaben bereinigen und als naechsten Schritt Kundenantwort beziehungsweise Nachfassdatum festhalten. Ist die Nachricht trotz Bestaetigung noch nicht auffindbar, die Bestaetigung dokumentieren und die technische Verifizierung als offen kennzeichnen.
