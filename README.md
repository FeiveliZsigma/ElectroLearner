# ElectroLearner

A free, dark-themed interactive learning platform for C++, ESP32 electronics, and Autodesk Fusion.

## Features
- SoloLearn-inspired course navigation and bite-sized lessons (original UI and content).
- C++ foundations with quizzes and a browser-based lesson-output simulator.
- ESP32 and Arduino lessons with hardware walkthroughs and a starter blink sketch.
- Fusion 360 first-project tutorial: setup, workspace, navigation, sketching, dimensions, extrusion, saving, and mesh export.
- XP, course progress, achievements, and learning streak tracking.
- Responsive layout for desktop and mobile.
- Progress saved locally in the browser with localStorage.

## Run locally
Open `index.html` in a modern browser. No build step or paid service is required.

## GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then Save.
4. Wait for GitHub Pages to publish the site.

The published URL will normally be:
`https://feivelizsigma.github.io/ElectroLearner/`

## Important limitations
- The C++ playground is a lightweight lesson simulator for the included examples, not a full native C++ compiler.
- The ESP32 simulator illustrates concepts; it does not emulate a physical board or upload firmware.
- Real ESP32 sketches must be compiled and uploaded using Arduino IDE or another compatible tool connected to the board.
- Fusion 360 tutorials guide the learner through Autodesk's separate desktop application; they do not control it.
- Progress is stored in the current browser/device. Cross-device accounts and cloud sync are not implemented yet.

ElectroLearner is an independent learning project and is not affiliated with SoloLearn or Autodesk.
