#### SSI: Nachteile

- Seite wird auf dem Server gebaut und "als Ganzes" ausgeliefert
  - erst wenn ALLE Micro Frontends fertig gebaut sind, wird etwas im Browser dargestellt
  - ein einzelnes fehlerhaftes Frontend kann die Gesamtanwendung negativ beeinflussen
- Größe der Anwendung(en) u.U. sehr hoch
- Kommunikation zwischen Apps limitiert durch URL-Parameter im SSI-Include
- Webserver muss SSI/ESI beherrschen
