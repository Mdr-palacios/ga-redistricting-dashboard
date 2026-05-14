# Drawing the Lines: A Georgia Redistricting Dashboard

A plain-language data visualization dashboard for Common Cause Georgia covering:

- An interactive map of Georgia's 14 congressional districts, with representative, partisan lean, and redraw risk
- How maps actually get drawn in Georgia (process step by step)
- What state law requires (and what it conspicuously does not)
- Four potential map-drawing scenarios for the June 17, 2026 special session

## Live site

This site is built as a single static page (`index.html`) plus one data file (`ga_cd119_compact.json`). It is served via GitHub Pages.

## Data sources

- District boundaries: US Census TIGERweb, 119th Congress, Georgia (state 13)
- Representatives and CPVI: Wikipedia, Cook Political Report
- Process and law: Georgia General Assembly Reapportionment Office, Ballotpedia, NCSL, Brennan Center for Justice

## Stack

- HTML, CSS, vanilla JavaScript
- Leaflet 1.9.4 for the interactive map
- CARTO basemap tiles
- No build step, no dependencies

## License and use

Common Cause Georgia, May 2026. Free for nonprofit voter education use.
