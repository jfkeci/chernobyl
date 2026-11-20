# chernobyl

A 3D visualization of the Chernobyl Unit 4 explosion (26 April 1986), built with [three.js](https://threejs.org/) in a single HTML file.

Live: https://jfkeci.github.io/chernobyl/

## Run

There is no build step. Serve the folder and open it in a browser:

```sh
python3 -m http.server 8067
# then open http://localhost:8067
```

three.js is loaded from a CDN, so an internet connection is required.

## What it shows

A timeline of about 42 seconds with seven captions: the turbine test at low power, the AZ-5 shutdown, the power surge, the two explosions, the burning open core with its glowing column of ionised air, and the aftermath. A HUD shows the local time and thermal power as the events unfold.

## Controls

| Control | Action |
| --- | --- |
| `Space` / Pause button | Play / pause |
| `R` / Replay button | Restart from the beginning |
| `S` / Slow-mo button | Toggle 0.25× speed |
| Drag / scroll | Orbit and zoom |

## Accuracy

This is an artistic reconstruction, not a physics simulation. The order and rough timing of the events follow the historical record, but the scene, the timescale and the readouts are simplified.
