# GIS_SS24
Parkplatz mit automatischer Kennzeichenerkennung, der Autos die durch den Eingang fahren erkennt und direkt zur Datenbank hinzufügt. Anstelle der Kamera muss der User sein Kennzeichen in der Simulation Manuell eintippen. Am Kassenautomat bezahlt man indem man sein Kennzeichen eintippt. Danach kann man ohne Schranke einfach rausfahren und die Kamera am Ausgang, welche in der App einem Manuellen Vorgang entspricht, löscht das Fahrzeug aus der Datenbank sofern man bezahlt hat. Im Fall, dass Kunden den Parkplatz verlassen ohne zu bezahlen werden die Kennzeichen Informationen gespeichert und der Kunde erhält eine Strafzettel. Erst nach dessen Bezahlung wird das Kennzeichen gelöscht. Da die Umsetzung mit der Automatischen Kennzeichenerkennung per Kamera nicht umsetzbar ist greife ich im Modell auf die Manuelle Eingabe der Kennzeichen informationen zurück. Beim Verlassen des Parkplatzes simuliere ich durch manuelles Entfernen des Kennzeichens (sofern bezahlt) den automatisierten Vorgang.
