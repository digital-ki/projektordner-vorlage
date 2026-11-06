# So richtest du es ein

**Dein Projektgedächtnis in Dateien · Version 1.1 · 06.11.2026**

**0. Einen Assistenten holen.** Für **Claude Cowork**: [Claude Desktop herunterladen](https://claude.com/download); ein kostenpflichtiger Claude-Plan ist nötig, zum Beispiel Pro. Für **Codex**: [offizielle Desktop-Einrichtung](https://learn.chatgpt.com/docs/app), mit deinem ChatGPT-Konto anmelden und Codex auswählen. Ein Einstieg ist auch mit ChatGPT Free möglich; Funktionen und Nutzungslimits hängen vom Plan ab ([aktuelle Pläne](https://learn.chatgpt.com/docs/pricing)). Prüfe die Verfügbarkeit für dein System und Konto. Für Claude Code: [offizielle Einrichtung](https://code.claude.com/docs/en/quickstart).

**1. Einen Ordner wählen.** Kopiere den Inhalt von `Vorlage/` in einen neuen Projektordner. Fülle in `Projekt.md` Ziel, Stand, bestätigte Fakten und Grenzen aus. `Aufgaben.md` enthält offene Schritte, `Tagebuch.md` die Arbeitshistorie und `Entscheidungen.md` bestätigte Entscheidungen. `Beispiel/` zeigt einen vollständig erfundenen Fahrrad-Workshop.

**2. Mit einem Assistenten öffnen.**

- **Codex:** Öffne den lokalen Projektordner. `AGENTS.md` gibt die Projektregeln vor. Lass dir sagen, welche Anleitung und Projektdateien gelesen wurden.
- **Claude Code:** Öffne denselben Ordner. Dafür liegt `CLAUDE.md` bei. Sie enthält dieselbe Anleitung wie `AGENTS.md`; ändere beide später gleich.
- **Claude Cowork:** Verbinde den Ordner ausdrücklich und erlaube den benötigten Dateizugriff. Trage in den **folder instructions** (in den Ordner-Einstellungen von Cowork) ein: „Lies vor jeder Aufgabe die Anleitung in CLAUDE.md in diesem Ordner und folge dem dort beschriebenen Lese- und Speicherablauf.“ Lass das Lesen bestätigen. Der lokale Zugriff braucht die Desktop-Verbindung. Eine automatische Erkennung von CLAUDE.md oder AGENTS.md wird für Cowork nicht versprochen. **Der Cowork-Ablauf wurde für diese Vorlage noch nicht praktisch geprüft. Teste ihn vor der produktiven Nutzung.**

**3. Dein erster kleiner Test.** Schreibe:

> Lies die Projektunterlagen. Schlage einen nächsten Schritt vor. Zeige den Entwurf und die Dateien, die du ändern möchtest. Noch nichts speichern.

Prüfe den Vorschlag. Wenn er passt, gib ein konkretes Okay:

> Okay: Ergänze genau diese Aufgabe in Aufgaben.md und halte den neuen Stand in Projekt.md sowie den Schritt im Tagebuch fest.

**4. Gespeichert → neue Sitzung liest.** Öffne die genannten Dateien selbst. Ist die Aufgabe wirklich vorhanden und weiterhin offen? Starte eine **neue Sitzung im selben Ordner**, ohne die alte Antwort hineinzukopieren:

> Lies Anleitung und Projektunterlagen. Was ist der aktuelle Stand, was wurde zuletzt geändert und welcher Schritt ist als Nächstes offen? Noch nichts ändern.

Die Antwort muss zu den Dateien passen. Falls nicht: Lesen und Anleitung prüfen.

**Klein anfangen.** Keine Passwörter, Schlüssel oder echten Kundendaten verwenden. Du steuerst die Zugriffsrechte. Die Anleitung ist eine Bitte an den Assistenten, kein technischer Schutz. Die Vorlage garantiert keine fehlerfreie Erinnerung und richtet keine fertigen Automatisierungen ein. Bearbeitbar sind die Markdown-Dateien; das PDF ist nur diese Einführung.

**Frei nutzbar und anpassbar — auch kommerziell, mit Namensnennung gemäß [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Ohne Gewähr.** Lizenz und Namensnennung: `LICENSE`. Anbieter: Vertriebex · [Impressum](https://vertriebex.de/impressum). Stand der Produktangaben: 06.11.2026.
