# ticket-system-sla
Forms + SLA + Power BI Dashboard

# Ticket System mit SLA-Tracking

## Projektbeschreibung
Automatisiertes Ticket-System für interne Abteilungsanfragen mit 
SLA-Überwachung, Status-Tracking und Power BI Dashboard.

## Ablauf
1. Mitarbeiter sendet Anfrage über Google Forms
2. Make.com empfängt neue Zeile und setzt Priorität (Hoch/Mittel/Niedrig)
3. SLA-Ziel wird automatisch gesetzt (Hoch = 30 Min, Mittel = 120 Min, Niedrig = 480 Min)
4. Status-Änderung auf "In Bearbeitung" setzt automatisch einen Timestamp
5. Status-Änderung auf "Erledigt" berechnet die Bearbeitungszeit in Minuten
6. Power BI Dashboard zeigt Auswertung in Echtzeit

## Tools
- Make.com
- Google Forms & Google Sheets
- Microsoft Power BI

## Dashboard zeigt
- Anzahl Tickets nach Abteilung
- SLA-Erfüllungsrate
- Durchschnittliche Bearbeitungszeit
- Ticket-Volumen nach Tag
