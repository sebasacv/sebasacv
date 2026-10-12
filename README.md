# Emily's Wanderbook

A geography and culture game for Emily, built around a live, spinnable globe.
Open `index.html` in any browser. It needs an internet connection for the map library and fonts.

## Modes

- **Mystery Trip**: Read clues about a country, starting with a local tradition, then a dish, how people say hello, a famous sight, and finally its flag and capital. Tap the globe to guess. Each wrong guess tells you how far off you are and which direction to head, and unlocks the next clue. Solve it and a plane flies from your last stop to the new country, then a passport stamp lands.
- **Pin It**: Ten rounds where you find a named country on the globe. Closer guesses score more, up to 1,000 points.
- **Explore**: Spin the globe and tap any country. 65 countries have a full culture page: greeting, food, tradition, must-see sight and a "did you know?" fact.
- **Passport**: Every stamp collected, with progress across the six inhabited continents. Your flight paths stay drawn on the globe.

Progress is saved in the browser's local storage.

Map data: [world-atlas](https://github.com/topojson/world-atlas) (Natural Earth, public domain). Rendering: [d3](https://d3js.org) and topojson-client.
