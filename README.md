# Native Android Lights Out Puzzle Game

A native Android mobile application that recreates the classic "Lights Out" logical matrix puzzle game, developed in Java using standard Android UI bindings.

## Technical Skills & Architecture
* **Matrix Logic Implementation:** Programmed a modular, 2D boolean array game engine (`LightsOutGame`) utilizing cellular automaton mechanics to flip states crosswise when a vertex is selected.
* **Algorithmic State Evaluation:** Developed state validation algorithms to systematically crawl the matrix grid and determine win conditions upon game-loop state updates.
* **Dynamic Event Binding:** Optimized UI performance by implementing linear indexing algorithms to map flat `GridLayout` children view indices into 2D multi-array row and column coordinates.
* **State Operations:** Configured matrix randomizing parameters to initialize dynamic, non-uniform puzzle instances for enhanced replayability.
