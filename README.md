# Guia de Mobilitat Escolar · eina de treball

Web interactiva basada en la guia **«Mobilitat escolar sostenible: Guia pràctica»** (setembre de 2026), d'Eduard Folch.

Ajuda a posar en marxa, pas a pas, el pla de mobilitat d'un centre educatiu:

1. **Comissió**: membres, rols, manifest de compromís, full de ruta i actes.
2. **Treball de camp**: qüestionari dels 8 blocs amb puntuació automàtica, punts crítics, indicador de calor i plànol d'isòcrones.
3. **Enquesta a famílies**: script per crear-la a Google Forms i importació del CSV de respostes.
4. **Triar solucions**: recomanacions basades en regles explícites, amb el perquè de cada una.
5. **Projectes**: fases, qui fa què, pressupost, indicadors i eines de cada fitxa, amb el text original de la guia.
6. **Seguiment i documents**: objectius, indicadors, comparativa de diagnosis i documents per imprimir.

Funciona sense IA i sense servidor: és un sol fitxer `index.html` i les dades es desen al navegador (amb exportació i importació en JSON).

Serveis externs que fa servir l'eina d'isòcrones: mapa d'OpenStreetMap / CARTO, isòcrones de Valhalla (FOSSGIS) i cerca d'adreces de Nominatim.


## Versions

- Català: `index.html`
- Castellano: `es/index.html` (selector CA/ES a la capçalera de l'eina)
