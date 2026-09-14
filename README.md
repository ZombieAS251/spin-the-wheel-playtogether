# Spin the Wheel Play Together

A browser-based lucky wheel game inspired by Play Together style prize selection. The app displays a 10-segment spinning wheel with animated lights, sound effects, confetti, and a winner modal showing the selected prize image.

## Features

- Interactive spinning wheel with 10 permanent prize slots
- Animated glowing light ring and visual effects
- Sound tick effects and winner fanfare
- Confetti celebration when a prize is selected
- Winner modal with the chosen image
- Responsive layout for smaller screens
- Static assets included for the wheel items and branding logo

## Project structure

```text
spin-the-wheel-playtogether/
├── README.md
└── project-folder/
    ├── index.html
    └── assets/
        ├── play-together.png
        ├── option1.png
        ├── option2.png
        ├── option3.png
        ├── option4.png
        ├── option5.png
        ├── option6.png
        ├── option7.png
        ├── option8.png
        ├── option9.png
        └── option10.png
```

## How to run

Because this is a static HTML project, you can either:

1. Open the file directly in a browser:
   - Open [project-folder/index.html](project-folder/index.html)

2. Or run a local web server from the project folder:

```bash
cd /workspaces/spin-the-wheel-playtogether/project-folder
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Notes

- The wheel always contains the same 10 options defined in the JavaScript array in [project-folder/index.html](project-folder/index.html).
- Prize images are loaded from the [project-folder/assets](project-folder/assets) folder.
- If you want to change the wheel items or branding, update the asset files and the matching item entries in the script.
