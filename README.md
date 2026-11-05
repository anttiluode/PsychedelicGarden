# Psychedelic Garden

Antti's Brain, planted. Built on the AnttisBrain2 "Descent" engine (one WebGL2 raymarching shader, hash-dreamed rooms, mirror moons, webcam boundary).

- Every moon hangs on a chain from the ceiling. A vine twines down each chain toward its moon, with leaves and glowing blooms. All of it is analytic SDF, so the moons reflect the vines and each other.
- **Goal:** each level hides one gold moon, the key. It sits in a cage of vine. The cage opens only when that room's garden has grown all the way down.
- **Growth comes from motion:** move in front of your webcam, or fly around the room. The HUD shows "garden here" and "your motion".
- Open the cage, touch the key, and the red seal on the far gate dissolves. Next level.

Controls: WASD move · Q/E down/up · Shift boost · drag to look.

Open `index.html` in a WebGL2 browser and allow the camera (the walls are you).

Status: the shader compiles and the game logic runs in a headless test. Frame rate on a real GPU is untested; the vines add a per-step cost to the raymarch.
