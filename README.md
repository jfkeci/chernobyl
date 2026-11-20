# chernobyl

A 3D visualization of the Chernobyl Unit 4 explosion (26 April 1986, 01:23:40), built with [three.js](https://threejs.org/) in a single HTML file.

## Run

There is no build step. Serve the folder and open it in a browser:

```sh
python3 -m http.server 8067
# then open http://localhost:8067
```

three.js is loaded from a CDN, so an internet connection is required.

## What it shows

A 34-second timeline covering the AZ-5 shutdown attempt, the power surge and the two explosions, followed by the fire and the aftermath figures.

- **Directed camera** with automatic slow motion around the explosions
- **Eight views** (keys `1`–`8`): directed, satellite, helicopter, ground, core close-up, Pripyat, free camera, and inside the core
- **Inside the core**: fuel channels coloured by heat, control rods jamming part-way in, neutrons and steam building up
- **Synthesized sound**: hum, alarm, explosions, fire and Geiger clicks (no audio files)

## Controls

| Control | Action |
| --- | --- |
| `Space` | Play / pause |
| `1`–`8` | Switch view |
| Timeline slider | Scrub to any moment |
| Speed button | Cycle 1× / 0.25× / 2× |
| Drag / scroll | Orbit and zoom (switches to the free camera) |

## Accuracy

This is a scripted illustration, not a physics simulation. The timing of the main events follows the historical record, but the readouts, the site layout and the core (about 170 channels instead of about 1,660) are simplified.
