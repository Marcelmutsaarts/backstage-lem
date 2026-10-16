# Backstage

Interactieve leeromgeving voor Leisure & Events Management. Proof of concept.

- `index.html`: de festivalkaart met tien activiteiten langs de levenscyclus van een evenement (idee, ontwerp, voorbereiding, uitvoering, evaluatie), met filters op fase, werkveld en studiejaar.
- `crowd.html`: activiteit 8, **Crowd Control**. Een 3D-festivalterrein met een live publiekssimulatie van tot 2.400 bezoekers.

## Crowd Control

Studenten zitten in de regiekamer van een avondfestival.

- **Drie scenario's**: deuren open (instroom), headliner (drukte voor het hoofdpodium) en onweer (ontruiming).
- **Regiekamer**: aantal bezoekers, beveiligingsstraten, wavebreaker met frontvak, tegenprogrammering, extra bar, extra nooduitgang en breedte van de uitgangen.
- **Live meten**: dichtheid in personen per m² (met drukte-kaart), wachttijd bij de bars, rij bij de ingang, ontruimingstijd en een belevingsscore.
- **Acht punten** met uitleg, praktijk, rekenvoorbeeld en denkvraag.
- **Zeven missies** volgens RTTI, met als slot een advies aan de gemeente.
- Gegenereerd geluid (publiek, beat, onweer) en een gesproken omroepbericht bij de ontruiming.

Het model is bewust eenvoudig en narekenbaar (6 bezoekers per minuut per straat, 60 personen per meter per minuut door een uitgang). Het is een leermodel, geen gecertificeerde crowd-simulatie.

## Techniek

Statische HTML zonder build-stap. 3D met three.js r147 via jsDelivr. Geen cookies, geen tracking, niets opgeslagen.
