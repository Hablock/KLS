# Kuntaliitossimulaattori v2

Yhden tiedoston interaktiivinen Suomen kuntien yhdistämissimulaattori
(index.html / suomen_kunnat_simulator.html). Inline SVG + vanilla JS,
ei kirjastoja, ei rakennusvaihetta.

## Datalähteet
- Kuntarajat: Maanmittauslaitos (kuntarajat.json), leikattu Natural Earth
  10m maa-alueella
- Asukasluvut: Wikipedia 31.3.2025
- Boundary-pituudet laskettu Shapelyllä leveysasteella 64°

## Tyyli
- Vastaa suomeksi
- Metric units kaikkialla
- Ei em-dasheja, ei emojeita
- Suorat, tiiviit vastaukset, ei LLM-täytefraaseja
- Säilytä yksitiedostorakenne, älä lisää kirjastoja ilman erillistä pyyntöä

## Tunnetut yksityiskohdat
- Pertunmaa (NATCODE 588) yhdistetty Mäntyharjuun (507) sekä geometriana
  että väkilukuna
- Saaristoyhteydet (Brändö/Sottunga ↔ Parainen) ovat virtuaalisia
  naapuruuksia ilman fyysistä rajaa, pituus 0 km