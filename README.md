# Setboek

Een webapp om krachttraining te loggen, gemaakt voor de iPhone. Open hem in Safari en zet hem via **Deel → Zet op beginscherm** op je beginscherm.

## Functies
- Trainingen loggen: kg, reps of tijd per set, afvinken, met lopende duur en volume
- Kolom "Vorige" met wat je de vorige keer deed
- Routines (vaste schema's) met één tik starten
- Rusttimer die na elke set start (−15 / +15 seconden)
- Persoonlijke records en voortgangsgrafieken per oefening
- Statistieken: laatste 12 weken, spiergroepen, kalender
- Eigen oefeningen, settypes (warming-up, dropset, tot falen), supersets, RPE en notities
- Back-up maken en terugzetten als bestand

## Je gegevens
Alles wordt alleen in de browser op je eigen apparaat opgeslagen (localStorage). Er is geen server en geen account. Maak af en toe een back-up via het tandwiel op Home en bewaar die bijvoorbeeld in iCloud Drive.

## Techniek
Eén HTML-bestand zonder afhankelijkheden, met een manifest en een service worker zodat de app ook offline werkt. Gehost via GitHub Pages.
