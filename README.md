# Chess Game App

This repository contains a desktop chess application packaged as `Chess-Game.jar`. This guide is for players who want to download the app, connect it to the Stockfish engine, and start playing chess.

## What you need

Before you run the app, make sure you have:

- a computer running Windows, macOS, or Linux
- Java installed on your machine
- the `Chess-Game.jar` file from this repository
- the Stockfish chess engine downloaded on your machine

## Step 1: Download the app

1. Open the repository on GitHub.
2. Download the project files.
3. Locate the file named `Chess-Game.jar`.
4. Save it somewhere easy to find, such as your Desktop or Downloads folder.

## Step 2: Download the Stockfish engine

The app needs the Stockfish engine in order to load a game.

1. Download Stockfish for your operating system.
2. Extract the downloaded files if needed.
3. Locate the Stockfish executable file on your computer:
   - **Windows:** usually `stockfish.exe`
   - **macOS/Linux:** usually `stockfish`
4. Remember the folder where this file is saved, because the app will ask you for it when you start a game.

## Step 3: Install Java if needed

The app is packaged as a JAR file, which means it requires Java to run.

To check whether Java is installed:

1. Open a terminal or command prompt.
2. Run:

```bash
java -version
```

If Java is installed, you will see a version number.
If it is not installed, install Java first, then try again.

## Step 4: Start the app

You can launch the app in either of these ways.

### Option A: Double-click the JAR file

On some systems, you can start the game by double-clicking `Chess-Game.jar`.

### Option B: Run it from the terminal

If double-clicking does not work:

1. Open a terminal or command prompt.
2. Go to the folder that contains `Chess-Game.jar`.
3. Run:

```bash
java -jar Chess-Game.jar
```

The application window should open.

## Step 5: Load the game with Stockfish

Once the application opens:

1. Click the **Play** button.
2. The app will prompt you to provide the location of the Stockfish engine.
3. Browse to the Stockfish executable you downloaded earlier.
4. Select that file.
5. After the Stockfish path is accepted, the game will load.

## Step 6: Play the game

After the game board appears:

1. Click a piece to select it.
2. Click the square where you want to move that piece.
3. Continue making moves to play the game.

The app is designed as a graphical desktop chess game, so you play directly on the board using your mouse.

## Tips for first-time players

- Download Stockfish before opening the app so you are ready when prompted.
- Make sure you choose the Stockfish executable file itself, not just the folder.
- If nothing happens when you click a piece, try selecting another legal move.
- If the board does not appear after choosing Stockfish, close the app and start again.

## Troubleshooting

### The JAR file does not open

Try launching it from the terminal with:

```bash
java -jar Chess-Game.jar
```

If that still fails, confirm that Java is installed.

### `java` is not recognized

Java is either not installed or not added to your system `PATH`. Install Java and try again.

### The app asks for Stockfish but I cannot find it

Go back to the folder where you extracted Stockfish and select the engine executable:

- `stockfish.exe` on Windows
- `stockfish` on macOS or Linux

### The game does not load after selecting Stockfish

Make sure:

- you selected the executable file itself
- you downloaded the correct Stockfish version for your operating system
- the Stockfish file was fully extracted before you selected it

## Quick start summary

1. Download `Chess-Game.jar`.
2. Download and extract Stockfish.
3. Install Java if needed.
4. Run `java -jar Chess-Game.jar`.
5. Click **Play**.
6. Select the Stockfish executable when prompted.
7. Start playing on the chessboard.
