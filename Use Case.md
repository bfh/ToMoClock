# ToMoClock


  Was brauchen wir:
  1. Internetverbindung
  2. Agenda/ Kalender
  3. persönlicher Zeitplan
  4. SBB Fahrplan


# Use Case
  1.	ToMoClock verbindet mit dem Internet
  2.	Eine Agenda erstellen
  3.	Ein Zeitplan erstellen , im Zeitplan steht die zeit , die man für die täglichen aufgaben braucht
      Z.b für duschen, aufstehen, Fruhstück . .usw
  4.	Der Transportfahrplan wird von einer Website oder app importiert , Z.b vom SBB App
  5.	Vergliechen zwischen alle 3 tablen (Agenda, Zeitplan, Transportfahrplan)
  6.	Rechnen um wie viel uhr muss man aufstehen
  
# Agenda
In der agenda muss ( die Addresse, Zeit und Datum) geschrieben sein



Use Case Tabelle
[Use Case.docx](https://github.com/bfh/ToMoClock/blob/master/Use%20Case.docx)



# MVP

```
TRAIN_TO_EVENT = 10min
BED_TO_TRAIN = 60min

currentLocation -> Ortname
googleCalendarEvent -> Ortname, DateTime

alarmClockTime = transportAPI(currentLocation.Ortname -> googleCalendarEventOrtname, googleCalendarEvent.DateTime - TRAIN_TO_EVENT) - BED_TO_TRAIN



