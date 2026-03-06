# Beach Landscape – A Python Turtle Art Project

This project creates a beautiful, calm beach scene using Python's `turtle` graphics module. It draws a gradient sky, glowing sun, fluffy clouds, a user‑provided sky message, a horizon haze, a single‑color calm sea, a textured sandy beach, palm trees, starfish, towels, umbrellas, footprints, and shells. The scene is completely **wind‑free** – palm fronds are straight, umbrellas are simple domes, and the ocean is still.

## Features

- **Interactive sky message** – You are prompted to enter a message that appears in the sky.
- **Gradient sky** – Smooth transition from deep blue at the top to light blue near the horizon.
- **Glowing sun** – Three overlapping glow layers, a bright core, and radial rays.
- **Fluffy clouds** – Each cloud is built from overlapping white circles.
- **Horizon haze** – A warm band where the sky meets the sea.
- **Calm sea** – A single, uniform blue rectangle.
- **Sandy beach** – Vertical gradient from dry sand to wet sand, with a dark wet‑sand strip.
- **Palm trees** – Straight trunks, trunk rings, straight‑line fronds (no curve), and coconuts.
- **Starfish** – Two five‑pointed starfish in different colors.
- **Towels** – Striped beach towels with fringe.
- **Umbrellas** – Simple domes with alternating coloured panels, a pole, and a knob.
- **Footprints** – A trail of six footprints in the sand.
- **Shells** – Spiral and clam shells scattered randomly.

All elements are drawn with precise layering to create a realistic, peaceful beach scene.

## Requirements

- Python 3.x (the `turtle` module is included in the standard library).
- No additional packages are needed.

## How to Run

1. Save the code in a file, e.g., `beach.py`.
2. Open a terminal or command prompt in that directory.
3. Run the script:
   ```bash
   python beach.py
   ```
4. A turtle graphics window will open and immediately show a dialog box asking for a sky message. Enter your message (or cancel to use the default "Hello, beach!").
5. After you close the dialog, the beach scene will be drawn and remain on screen.

## Code Structure

The code is organized into logical sections:

- **Setup**: Screen configuration, user input, turtle creation, random seed.
- **Helper function** `rect()` for drawing filled rectangles.
- **Sky gradient** using a loop and `rect()`.
- **Sun** with glow layers and rays.
- **Clouds** using a `puff()` helper.
- **User message** with `write()`.
- **Horizon haze**.
- **Sea** (one color).
- **Sand gradient** and wet strip.
- **Palm tree function** `palm()` with trunk, rings, straight fronds, coconuts.
- **Starfish function** `star()`.
- **Towel function** `towel()`.
- **Umbrella function** `umbrella()` with alternating wedges.
- **Footprints** loop.
- **Shell function** `shell()` with spiral and clam types.
- **Placement** of trees, umbrellas, starfish, towels, footprints, and shells.
- **Final update** and main loop.

## Customization

You can easily modify the scene:

- Change the sky message by editing the default or entering a new one.
- Adjust colours, sizes, or positions of any element.
- Add or remove elements as desired.

## Acknowledgments

This project was created as an artistic expression of a calm, wind‑free beach using simple turtle graphics. It demonstrates how code can produce detailed, layered illustrations.

Enjoy your virtual beach day!
