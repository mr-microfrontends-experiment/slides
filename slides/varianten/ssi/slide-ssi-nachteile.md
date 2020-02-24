#### SSI: Nachteile

- Seite wird auf dem Server gebaut und "als Ganzes" ausgeliefert
  - erst wenn **alle** Micro Frontends fertig gebaut sind, sieht der User etwas
  - ein einzelnes fehlerhaftes Frontend kann die Gesamtanwendung negativ beeinflussen
- Gesamtgröße der Anwendung(en) u.U. sehr hoch
- Kommunikation zwischen Apps limitiert durch URL Parameter im SSI include
- Webserver muss SSI/ESI beherrschen
