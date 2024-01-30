## Chain Reaction Game
Welcome to the Chain Reaction Game project! This is a simple yet challenging multiplayer strategy game implemented in Python. The game is inspired by the popular board game "Chain Reaction" and aims to provide an engaging and entertaining gaming experience.

### About the Game
Chain Reaction is a turn-based game where players strategically place their orbs on the game board. The goal is to create chain reactions by placing orbs adjacent to existing ones, causing them to explode and trigger a cascade of reactions. The player who strategically manages their orbs and captures the maximum number of cells on the board emerges victorious.

### Game Features
- **Multiplayer Support:** Play against friends or random opponents online.
- **Customizable Board:** Choose different board sizes and configurations for varied gameplay.
- **Intuitive Controls:** Simple and user-friendly controls for placing orbs on the board.
- **Scoring System:** Track your progress with a scoring system that rewards strategic thinking.

### Technologies Used

- **HTML & CSS:** The game's structure, layout, and styling are built using HTML and CSS.
- **JavaScript Framework (Node.js):** Node.js is a runtime that allows JavaScript to be used on the server side, enabling the development of scalable and fast server applications. In the context of the Chain Reaction Game, Node.js is likely used for server-side logic, handling backend functionality, and supporting real-time communication between clients.
- **Flask:** Flask is utilized for the frontend, enabling dynamic and interactive web pages.



### How to Play
1. The gameplay takes place on an m×n board. The most commonly used size of the board is 9×6.
2. For each cell on the board, we define a critical mass. The critical mass is equal to the number of orthogonally adjacent cells. That would be 4 for usual cells, 3 for cells in the edge, and 2 for cells in the corner.
3. All cells are initially empty. The Red and the Green players take turns to place "orbs" of their corresponding colors. The Red player can only place a (red) orb in an empty cell or a cell that already contains one or more red orbs. When two or more orbs are placed in the same cell, they stack up.
4. When a cell is loaded with a number of orbs equal to its critical mass, the stack immediately explodes. As a result of the explosion, to each of the orthogonally adjacent cells, an orb is added and the initial cell loses as many orbs as its critical mass. The explosions might result in an adjacent cell overload, and the explosion's chain reaction continues until every cell is stable.
5. When a red cell explodes and there are green cells around, the green cells are converted to red and the other rules of explosions still follow. The same rule applies to other colors.
6. The winner is the one who eliminates every other player's orbs.

### Getting Started
To get started with the Chain Reaction Game, follow these steps:

[Clone or download the repository]
[Install any dependencies]
[Run main.py and follow the link]

### Contributors
This project wouldn't have been possible without the collaborative efforts of the following team members:
- [Darrien](https://github.com/darry002)
- [Dennis Andrew](https://github.com/denni-andr)
- [Deepesh](https://github.com/deepesh2110160)

### Contributing
If you'd like to contribute to the project, feel free to fork the repository and submit pull requests. We welcome contributions in the form of bug fixes, new features, or improvements to the existing codebase.
