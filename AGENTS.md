# Arbeitsfortsetzung in neuen Sitzungen

Wenn eine neue OpenCode-Sitzung in diesem Verzeichnis beginnt oder der Nutzer ohne weiteren Kontext sinngemäß „weiter“ sagt, frage nicht zuerst, womit du weitermachen sollst.

Prüfe stattdessen selbstständig den aktuellen Arbeitsstand im Repository, insbesondere:

- `git status`, vorhandene Diffs und die letzten Commits,
- Planungs-, Aufgaben- und Statusdateien,
- noch nicht abgeschlossene oder nicht verifizierte Änderungen,
- relevante Projekt- und Entwicklerdokumentation.

Leite daraus den zuletzt bearbeiteten Arbeitskontext und den sinnvollsten nächsten Schritt ab. Berichte dem Nutzer kurz, was du gefunden hast, und setze die Arbeit anschließend fort, sofern der nächste Schritt eindeutig und sicher ist.

Stelle erst dann eine gezielte Rückfrage, wenn die Prüfung keine belastbare Fortsetzung ermöglicht, mehrere wesentlich unterschiedliche Arbeitsrichtungen offen sind oder eine riskante beziehungsweise irreversible Entscheidung erforderlich wäre. Verwirf oder überschreibe niemals vorhandene Änderungen, nur um einen vermeintlich sauberen Ausgangszustand herzustellen.

## Verbindliches Sitzungsprotokoll in RS-LED.md

Die Datei `RS-LED.md` MUSS in jeder OpenCode-Sitzung eigenstaendig und fortlaufend mitprotokolliert werden. Zu Beginn jeder Sitzung die Datei lesen und mit dem Repository-, Twenty- und Mail-Stand abgleichen. Waehrend der Arbeit beziehungsweise spaetestens vor Sitzungsende alle wesentlichen ausgefuehrten Arbeiten, Entscheidungen, Verifizierungen, Commits, offenen Punkte, Blocker und den naechsten belastbaren Schritt nachtragen.

Das Protokoll muss den tatsaechlichen Stand wiedergeben. Entwuerfe duerfen nicht als versendet, unbestaetigte Annahmen nicht als Fakten und ausstehende Antworten nicht als Freigaben dokumentiert werden. Bereits erledigte oder ueberholte Punkte sichtbar aktualisieren, statt widerspruechliche Parallelstaende stehen zu lassen.

`RS-LED.md` ist das technische Sitzungs- und Uebergabeprotokoll fuer OpenCode. Twenty bleibt die alleinige verbindliche Quelle fuer CRM-Daten und die zugehoerige Wissensbasis. Kundendaten und Wissenseintraege deshalb weiterhin in Twenty pflegen und in `RS-LED.md` nur den fuer die Arbeitsfortsetzung erforderlichen Status festhalten.

## Twenty CRM und Wissensbasis

Twenty ist fuer dieses Projekt die alleinige verbindliche Quelle fuer CRM-Daten und die zugehoerige Wissensbasis. Bei relevanten Aenderungen, Neuinstallationen, Erkenntnissen oder Caveats die passenden Datensaetze beziehungsweise Wissenseintraege in Twenty pflegen. Bestehende Datensaetze gezielt aktualisieren und keine parallele Dokumentation in einem anderen System anlegen.

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

Jede neu verfasste E-Mail an einen externen Kunden muss ausnahmslos zuerst als interner Pruefentwurf an Georg unter `g.schroejahr@rs-led.de` gehen. Vor Georgs nachgewiesener Freigabe der exakten Fassung darf kein an den Kunden adressierter Entwurf angelegt werden. Die interne Pruefmail und Georgs Antwort sind gemaess dem bestehenden Pruefprozess im Postfach zu verifizieren und in Twenty zu dokumentieren. Verlangt Georg Aenderungen oder wird der Text danach anderweitig inhaltlich geaendert, muss auch die neue Fassung erneut zuerst an Georg; eine Freigabe einer frueheren Fassung reicht nicht aus.

Fremde Kunden- und Projektnamen sowie andere identifizierende Angaben aus Referenzprojekten duerfen in E-Mails an Kunden nicht genannt werden. Dazu gehoeren insbesondere Namen wie `Buettner`, konkrete Angebotsnummern, Ansprechpartner und interne Projektbezeichnungen. Referenzbilder und Renderings ausschliesslich neutral als Beispiel einer `vergleichbaren Loesung` oder eines `vergleichbaren Projekts` bezeichnen. Interne Pruefmails an Georg duerfen die Quelle zur eindeutigen Zuordnung nennen; der darin enthaltene Kundenmailtext muss bereits anonymisiert sein.

Die Absendersignatur ist in Outlook fest hinterlegt. OpenCode schreibt deshalb in E-Mail-Entwuerfe ausschliesslich den eigentlichen Nachrichtentext und fuegt weder Grussformel noch Absendername, Kontaktdaten, Firmenangaben oder einen HTML-/Text-Footer hinzu. Die Outlook-Signatur darf nicht nachgebaut, dupliziert oder verwaltet werden. Bei der Entwurfspruefung nur sicherstellen, dass der von OpenCode erzeugte Nachrichtentext keine manuelle Signatur enthaelt.

Keine Bilder selbst in E-Mail-Entwuerfe einbetten oder als Anhang hinzufuegen. Der Nutzer fuegt Bilder im Mailprogramm eigenstaendig hinzu. Einen gewuenschten Hinweis auf Bilder im Mailtext darf OpenCode formulieren, die Bilddateien selbst aber nicht anfassen. Andere Anhaenge nur auf ausdruecklichen Auftrag hinzufuegen.

Ausnahme fuer ausdrueckliche Weiterleitungen bestehender E-Mails: Wenn der Nutzer nur anweist, eine vorhandene E-Mail weiterzuleiten, keine neue Nachricht verfassen. Keinen eigenen Einleitungstext, keine zusaetzliche Anrede und keinen Hinweis oder Trenner wie `Weitergeleitete Nachricht` beziehungsweise `Forwarded message` einfuegen. Alle Originalanhaenge vollstaendig uebernehmen, ausdruecklich auch vorhandene PNG-, JPG- oder sonstige Bildanhaenge. Den sichtbaren Originaltext ohne vorgestellte Ergaenzungen uebernehmen, aber fremde beziehungsweise doppelte Signaturen und Footer entfernen. OpenCode fuegt auch bei Weiterleitungen selbst keinen Footer ein; die Absendersignatur kommt ausschliesslich aus Outlook. Empfaenger, CC, BCC, Betreff, vollstaendige Anhangsliste und das Fehlen einer manuell eingefuegten Signatur vor Abschluss pruefen.

Wenn der Nutzer bei einem E-Mail-Auftrag ohne weitere Adressangabe `Georg` als Empfaenger nennt, ist damit immer `g.schroejahr@rs-led.de` gemeint. Eine abweichende Adresse nur verwenden, wenn der Nutzer sie ausdruecklich nennt.

Den Nutzer nach Abschluss einmal knapp und eindeutig ueber `Entwurf angelegt` beziehungsweise `nicht versendet` informieren. `can_send: false` nicht bei jedem Zwischenschritt erneut erklaeren, nicht wiederholt als Problem hervorheben und nicht staendig dieselbe manuelle Versandaufforderung wiederholen. Nur erneut darauf eingehen, wenn der Nutzer nach dem tatsaechlichen Versandstatus fragt, ein vermeintlicher Versand verifiziert werden muss oder sich die Mail-Faehigkeiten des Kontos geaendert haben.

Wenn der Nutzer ausdruecklich anweist, eine Mail an den anfragenden Kunden rauszuschicken, zuerst nur den internen Pruefentwurf an Georg anlegen. Erst nach Georgs im Postfach nachgewiesener Freigabe der exakten Fassung den Kundenentwurf anlegen oder aktualisieren und danach genau einmal fragen, ob der Nutzer die Mail im Postfach versendet hat. Diese einmalige Versandnachfrage ist beabsichtigt und keine erneute Erklaerung von `can_send: false`. Eine Versandfreigabe oder ein Entwurf allein darf niemals als tatsaechlicher Versand dokumentiert werden.

Nach der Versandbestaetigung den Gesendet-Ordner nach Empfaenger und Betreff pruefen. Bei erfolgreicher Verifizierung den zugehoerigen Kundenvorgang beziehungsweise die Opportunity und die passende Aufgabe in Twenty auf `versendet` beziehungsweise `Versandauftrag erledigt` aktualisieren, Versandzeit und Nachrichten-ID dokumentieren, veraltete Entwurfsangaben bereinigen und als naechsten Schritt Kundenantwort beziehungsweise Nachfassdatum festhalten. Ist die Nachricht trotz Bestaetigung noch nicht auffindbar, die Bestaetigung in Twenty dokumentieren und die technische Verifizierung als offen kennzeichnen.
