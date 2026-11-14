# Abandoned but Not Forgotten (Project Orbit One)

A story-driven website for school-age space fans about the hardware NASA has left on the Moon, on Mars and in deep space. Made for the **2026 NASA Space Apps Challenge**, challenge: *Abandoned but not Forgotten: Storytelling about NASA's Discarded Equipment on the Moon and Mars*.

**Live site:** [Click Here](https://nevinbeno.github.io/orbit-one/) 

## What it does

- Tells the story of 11 pieces of hardware: Surveyor 3, the Apollo science instruments and mirrors, the Apollo 11 Lunar Module descent stage, the Lunar Roving Vehicle, Pioneer 10, the Viking landers, Voyager 1, Sojourner, Spirit, Opportunity and Ingenuity.
- Each card has a first-person line in the machine's own voice, what it did, its status today, what scientists learned from it, and a link to its NASA source page.
- A clickable timeline, Moon / Mars / Deep space filters and a six-question quiz.
- A canvas-drawn animated sky (twinkling stars, a ringed planet, shooting stars and click sparkles). It stays still for people who prefer reduced motion.

## How it is built

Plain HTML, CSS and JavaScript in a single file (`index.html`). No frameworks, no build step, no external libraries. All content lives in one `items` list near the bottom of the file, and the timeline and cards are generated from it.

To run it locally, open `index.html` in any browser.

## NASA sources

- [NASA Space Science Data Coordinated Archive (NSSDCA)](https://nssdc.gsfc.nasa.gov/)
- [Apollo 11 Lunar Module](https://nssdc.gsfc.nasa.gov/nmc/spacecraft/display.action?id=1969-059C)
- [Lunar Roving Vehicles](https://nssdc.gsfc.nasa.gov/nmc/spacecraft/display.action?id=1971-063C)
- [ALSEP Scientific Packages](https://nssdc.gsfc.nasa.gov/nmc/spacecraft/display.action?id=1969-099C)
- [Surveyor 3](https://science.nasa.gov/mission/surveyor-3/)
- [Mars Pathfinder / Sojourner](https://science.nasa.gov/mission/mars-pathfinder/)
- [Spirit & Opportunity](https://science.nasa.gov/mission/mars-exploration-rovers-spirit-and-opportunity/)
- [Viking](https://science.nasa.gov/mission/viking-1/)
- [Pioneer 10](https://science.nasa.gov/mission/pioneer-10/)
- [Ingenuity](https://science.nasa.gov/mission/mars-2020-perseverance/ingenuity-mars-helicopter/)
- [Voyager](https://science.nasa.gov/mission/voyager/)
