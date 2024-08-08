### Lights Out Puzzle Game

**Overview:**
*Lights Out* is a logic puzzle game implemented in React. The game consists of a grid of lights that can be toggled on or off by clicking. Clicking a cell not only toggles its state but also affects adjacent cells (up, down, left, right). The objective is to turn off all the lights to win the game.

**Components:**
- **App:** Simple top-level component rendering the *Board*.
- **Board:** Manages the game state and renders a grid of *Cell* components. Handles the logic for toggling cells and checking win conditions.
- **Cell:** Represents each individual cell in the grid. Clicking a cell toggles its state and potentially adjacent cells.

**Features:**
- Dynamic grid size configurable through props.
- Responsive design using CSS Grid for layout.
- Win detection logic implemented to check when all lights are turned off.

**Technologies Used:**
- React: State management and component lifecycle handling.
- CSS Grid: Layout for the game board.
- JavaScript: Event handling and game logic implementation.

**Purpose:**
This project serves as a practical exercise in managing React state, handling events across nested components, and implementing a classic logic puzzle game. It demonstrates proficiency in React component design, state management, and interactive user interfaces.
