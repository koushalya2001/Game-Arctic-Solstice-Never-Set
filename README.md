# Arctic Solstice: Never Set

**June as a month of endurance, liberation, balance, and care**

Arctic Solstice: Never Set is a browser-based side-scrolling survival game inspired by the June Solstice Game Jam theme. The game places the player in an Arctic Circle landscape under the midnight sun, where constant daylight becomes both a visual wonder and a survival challenge.

The experience blends movement, yoga-inspired recovery, codebreaking, reflection, and environmental pressure into one atmospheric journey.

## Play the game

- Local file: `arctic-solstice-never-set-local-server.html`
- GitHub Pages: deploy the same file as `index.html`

## Core idea

The game is built around a simple narrative:

- **Solstice** creates endless daylight and exposure.
- **Yoga** helps the player recover stamina and focus.
- **Turing-inspired decoding** opens a signal gate through pattern recognition.
- **Juneteenth-inspired freedom imagery** marks the path toward liberation.
- **Father’s Day reflection** turns the final stretch into a personal memory moment.

The goal is to survive the Arctic sun, learn from the environment, and finish the journey with both mechanical and emotional progress.

## Features

- **Arctic Circle environment** with a visible midnight sun and icy terrain.
- **Side-scrolling movement** using arrow keys.
- **Yoga recovery mechanic** that restores stamina and focus in shaded areas.
- **Polar bear chase pressure** for tension and urgency.
- **Turing signal gate** with a rotating code-ring interaction.
- **Gemini guide avatar** at the bottom of the screen for adaptive hints.
- **Audio intro** plus text-based game introduction.
- **Reflection stage** for a more personal Father’s Day moment.

## Controls

- **Left / Right arrow keys**: Move.
- **Up arrow**: Jump.
- **E**: Practice yoga in shade or rotate the SHIFT gate.
- **R**: Reflect at the memory cairn.
- **Gemini orb**: Ask for a live hint or spoken guidance.

## Gemini integration

The game supports a temporary Gemini API key field for local testing.

- If you paste a key at the start screen, the Gemini guide can call the Gemini API for live hints.
- If you leave it blank, the game still works with built-in fallback hints.
- The guide can also speak hints through the browser’s speech synthesis.

For production, keep the API key server-side and use secure token patterns instead of exposing a long-lived key in the browser.

## Files

- `arctic-solstice-never-set-local-server.html` — main game file.

## How to run locally

### Option 1: Python

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/arctic-solstice-never-set-local-server.html
```

### Option 2: VS Code Live Server

1. Open the project folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click the HTML file.
4. Choose **Open with Live Server**.

## How to deploy on GitHub Pages

1. Rename `arctic-solstice-never-set-local-server.html` to `index.html`.
2. Create a GitHub repository.
3. Push the file to the repository root.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, select the branch and folder containing `index.html`.
6. Save and wait for the Pages URL to activate.

## Suggested repository structure

```text
/
├─ index.html
└─ README.md
```
