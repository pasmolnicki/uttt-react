### UTTT React

This is a Node.js React mode for playing the Ultimate Tic-Tac-Toe game with MCTS engine.

You can visit the live demo [here](https://uttt.up.railway.app).

> [!NOTE]
> This is project only runs the frontend, a backend server is required to run the analysis. This is made for view-only and does not perform any analysis itself. The backend itself is written in Go and uses the [go-mcts](https://github.com/pasmolnicki/go-mcts) library. However, for security reasons (or due to my bad practices), the source code is not publicly available.

### Installation

Simply clone the repo and install the dependencies:

```bash
git clone https://github.com/pasmolnicki/uttt-react.git
cd uttt-react
npm install
```

### Running

```bash
npm run dev
```