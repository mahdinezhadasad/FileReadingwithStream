# PostleitZahl Anwendung

## Beschreibung

Dies ist eine Java-Konsolenanwendung, die bei Eingabe einer fünfstelligen Postleitzahl den entsprechenden Ort (Stadt) anzeigt. Zusätzlich können bei Eingabe eines Ortsnamens alle verfügbaren Postleitzahlen (PLZ) für diesen Ort angezeigt werden. Die Anwendung liest die Daten aus einer CSV-Datei (`plz_ort(in).csv`) und verarbeitet diese.

### Features:
- Suche nach Orten anhand einer fünfstelligen Postleitzahl.
- Suche nach allen Postleitzahlen zu einem bestimmten Ort.
- Daten werden aus einer CSV-Datei geladen und in einer Liste von `Location`-Objekten verarbeitet.
- Die Anwendung ist vollständig kompatibel mit Java 8.

## Voraussetzungen

- Java 8 oder höher muss auf dem System installiert sein.
- Die Datei `plz_ort(in).csv` muss im Projektverzeichnis vorhanden sein. Diese Datei sollte in folgendem Format vorliegen:

  ```csv
  osm_id,ort,plz,bundesland
  123456,Dortmund,44135,Nordrhein-Westfalen
  123457,Dortmund,44137,Nordrhein-Westfalen
  123458,Dortmund,44139,Nordrhein-Westfalen
