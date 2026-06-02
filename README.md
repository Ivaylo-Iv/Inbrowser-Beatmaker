# Inbrowser Beatmaker

An in-browser drum sequencer built with vanilla JavaScript, HTML, and SCSS. Create quick drum patterns by toggling steps in an 8-step grid, swapping samples, muting tracks, and adjusting the tempo in real time.

## Features

- 8-step sequencer for kick, snare, and hihat tracks
- Play and stop playback with a single button
- Per-track sample selection for each drum lane
- Per-track mute controls
- Tempo slider for faster or slower patterns
- Active-step animation to show playback progress

## How It Works

Each track contains eight pads. Click a pad to activate or deactivate it, then press Play to loop the pattern. During playback, the app advances through the grid step by step and triggers the selected audio sample whenever an active pad is reached.

## Running The Project

This project does not require a build step or package install.

1. Clone or download the repository.
2. Open `index.html` directly in a browser, or serve the folder with a local static server.

If you prefer a local server, any simple static server will work.

## Controls

- Kick, snare, and hihat rows each have eight pads.
- Use the dropdown menus to switch between the available drum samples.
- Use the mute button on each track to silence or restore it.
- Use the tempo slider to change the playback speed.
- The Play button starts and stops the sequencer.

## Project Structure

- `index.html` - Main interface and audio elements
- `js/app.js` - Sequencer logic and event handling
- `style/` - SCSS source files and compiled CSS
- `sounds/` - Drum samples used by the sequencer

## Built With

- HTML5
- SCSS / CSS
- Vanilla JavaScript
- Font Awesome for the mute icon

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
