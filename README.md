CMMN translations
================

Translation of CMMN (Case Management Model and Notation) terms used in "Praxishandbuch BPMN (Auflage 5)".

## Allgemeine Begriffe

CMMN notation        | German         
-------------------- | ----------------- 
Case                 | Fall
Case File            | Fallmappe
Case File Item       | Falldokument
Task                 | Aufgabe
Human Task           | Benutzer-Aufgabe
Case Task            | Fall-Aufgabe
Process Task         | Prozess-Aufgabe
Stage                | Abschnitt
Milestone            | Meilenstein
Sentry               | Wächter
Planing Table        | Planungstabelle
Entry Criterion      | Eintrittsbedingung
Exit Criterion       | Ausstiegsbedingung  
On part              | Wächterereignis
If part              | Wächterbedingung   
Event Listener       | Ereignis
User Event Listner   | Benutzerereignis
Timer Event Listener | Zeitereignis

## Lebenzyklus Zustände & Transitionen

See also [translated lifecycle](lifecycle.pdf)

CMMN Transitions | Deutsch                 | x | CMMN Lifecycle  | German      
---------------- | ----------------------- | - | --------------- | ---------------
create           | erzeugen                |   | available       | vorhanden      
enable           | ermöglichen             |   | enabled         | möglich   
disable          | sperren                 |   | disabled        | gesperrt       
re-enable        | entsperren              |   |
start            | starten                 |   | active          | aktiv   
manual start     | manuell starten         |   | 
suspend          | pausieren               |   | suspended       | pausiert
resume           | fortsetzen              |   |
parent suspend   | ? Elternteil pausieren  |   |
parent resume    | ? Elternteil fortsetzen |   |
fault            | fehlschlagen            |   | failed          | fehlgeschlagen
re-activate      | reaktivieren            |   |
terminate        | beenden                 |   | terminated      | beendet
exit             | verlassen               |   |
complete         | erledigen               |   | completed       | erledigt
close            | schließen               |   | closed          | geschlossen
