# chess-like-game
## Project overview

A turn-based chess-like game played on a 5x5 grid where two players control teams of pieces with unique movement rules. The game supports real-time play using WebSockets for communication between clients and server.

![Screenshot 2024-08-27 181337](https://github.com/user-attachments/assets/7034970a-fae0-4601-9538-d536ccfafae0)

```markdown
## Project Structure

/AyushRathi_21BEC0844
├── /client
│   ├── index.html
│   ├── style.css
│   └── client.js
├── /server.js
├── package.json
└── package-lock.json
```

### Client Directory

- **`index.html`**: Contains the HTML layout for the game board.
- **`style.css`**: Provides the styling for the game board and pieces.
- **`client.js`**: Implements the game logic and handles user interactions.

### server.js:
- Sets up an Express server and WebSocket communication for real-time game updates.

## Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ayushrathi2412/AyushRathi_21BEC0844.git

2. **Install Dependencies:**
   ```bash
   npm install

3. **Start the Server and this will too view the game**
   ```bash
   npm start

   
```markdown
## How to Play

   -Click on a piece to select it.
   -Click on a highlighted square to move the piece.
   -The turn indicator updates to show whose turn it is.
   -The game notifies you when a player wins.
```

![Screenshot 2024-08-27 182142](https://github.com/user-attachments/assets/ce248c8c-f1ce-4bc9-868f-352b8cd4dac5)
## Player B wins

```markdown
## Dependencies

   -Express: Web server framework.
   -ws: WebSocket library for real-time communication.
```
```markdown
## License

   -This project is licensed under the MIT License. See the LICENSE file for details.
```
```markdown
## Acknowledgments

   -Special thanks to HitWicket for the opportunity to showcase my skills and express my interest in the company.
   -Gratitude to the open-source community for providing tools and libraries that made this project possible.
```

