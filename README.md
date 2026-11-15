# Three Silences

**Three places where our machines went silent: the Moon, Mars and deep space.**

An interactive website for explorers aged 8–12, telling the stories of the machines humanity left behind. Every machine tells its own story in simple words, next to real facts checked against NASA records.

Made for the **NASA Space Apps Challenge 2026** challenge *Abandoned but not Forgotten: Storytelling about NASA's Discarded Equipment on the Moon and Mars*.

**▶ Live demo:** https://fjord000.github.io/three-silences/

---

## Four ways in

| | Part | What you do |
|---|---|---|
| 1 | **Ghost Rovers** | Spin a 3D Moon or Mars, tap a glowing dot and land beside the machine. A time slider replays every landing since 1966. A signal-delay experiment shows why Mars rovers can't be driven live, and you can drive a rover yourself. |
| 2 | **Sleep Mode** | A short comic told by MIRA-4, a fictional Mars lander, as dust slowly covers its solar panels. |
| 3 | **3D Hangar** | 22 spacecraft as 3D models (15 of them real models). Tap a part to light it up, add dust to solar panels and answer a quiz. Includes the "landing leftovers": heat shields, parachutes and sky cranes. |
| 4 | **The Last Tuning** | A five-episode podcast about an instrument's last days. Each episode ends with a real fact about the Voyager Golden Record. |

## Run it

- **Online:** open the GitHub Pages link above.
- **On your computer:** download the folder and open `index.html` in a modern browser. Keep the `models` folder next to it. An internet connection is needed, because three.js and the fonts load from a CDN.

Each 3D model is loaded only when someone opens it, so the page itself is small (about 0.3 MB).

## Folder

```
index.html        the whole site: HTML, CSS and JavaScript
models/*.js       real 3D models, one file each, loaded on demand
.nojekyll         tells GitHub Pages to serve the files as they are
```

## Built with

- HTML, CSS and JavaScript, with [three.js](https://threejs.org) r128 (MIT License)
- Web Audio API for the piano and Web Speech API for the narration (the podcast is read aloud by the device's own voice)
- 3D models converted and simplified in the browser with three.js loaders, [TinyUSDZ](https://github.com/lighttransport/tinyusdz) and [meshoptimizer](https://github.com/zeux/meshoptimizer)

## Sources

Mission facts were checked against NASA Science mission pages and the NASA NSSDCA catalogue, including:

- **Moon:** Apollo 11, Apollo 12 and Apollo 15 Lunar Modules; Surveyor 3
- **Mars:** Viking 1, Mars Pathfinder, Spirit and Opportunity, InSight, Ingenuity, Curiosity and Perseverance
- **Deep space:** Mariner 4, Pioneer 10, Kepler, Dawn and NEAR Shoemaker
- **Voyager:** the Voyager Golden Record and the Voyager mission updates
- **Other countries' rovers:** NASA Lunar Reconnaissance Orbiter (LRO) images of Lunokhod 1 and 2, Chang'e 3 and Yutu, Chang'e 4 and Yutu-2, and the Chandrayaan-3 landing site

The full list of links is at the bottom of the site.

## 3D model credits

- "Mariner 4 Spacecraft" by Salatiel, Sketchfab, CC BY 4.0
- [Add the source and licence of each other model here: Apollo Lunar Module, Lunar Roving Vehicle, Viking Lander, Opportunity, Spirit, Curiosity, Perseverance, InSight, Sojourner, Voyager, Pioneer 10, Kepler, Dawn, NEAR Shoemaker]

The Moon and Mars globes, the simpler models, the comic art and the piano sounds are generated in code for this project.

## Facts and fiction

- **Real:** every "From the records" fact comes from NASA sources.
- **Fiction:** every machine's voice is fiction. MIRA-4 and Leyla (the piano) are made up, and both are clearly labelled.
- **Other countries:** rovers from other countries are shown as neighbours that NASA's LRO photographed from orbit, and are labelled "not NASA".

## Use of AI

The software was built with the help of an AI assistant, Claude by Anthropic, which wrote the code from our direction and converted the 3D models. We researched and checked the facts, chose and prepared the models, decided the story and design, tested everything and reviewed the results.

## Team

Intelligent Gravity-free Nova Insights for Safety (IGNIFS) - Yusa Emre Arıc  
