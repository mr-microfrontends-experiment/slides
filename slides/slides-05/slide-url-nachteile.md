#### Aufteilen über URL - Nachteile

* Gesamtgröße der Anwendung(en) sehr hoch
 * Jedes "Micro"-Frontend bringt den vollen Framework-Ballast mit
 * Oft werden gleiche Bibliotheken mehrfach geladen
* Kommunikation zwischen Apps limitiert durch URL
* Schneiden nach "Seiten", nicht nach "Themen"
  * Nur eine App pro sichtbarer Seite
  * gleiche Funktion in mehreren Seiten schwierig