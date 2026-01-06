# CHESS-GAME

# ♟️ JavaScript Chess Game by Akash

This is a **fully functional Chess Game** built using **HTML**, **CSS**, and **JavaScript (with jQuery)**.  
It features a custom-designed chessboard, animated styling, and interactive gameplay logic to move chess pieces.  
I built this project to strengthen my JavaScript logic and DOM manipulation skills.

---

## 🌐 Live Demo

👉 [Play the Game](chess-game-omega-eight.vercel.app)

---


## 🎮 About the Project


This project recreates a simplified version of **Chess** inside the browser.  
It uses **HTML div elements** to represent each square on the chessboard, dynamically rendered and color-coded using CSS.  
The **script.js** file handles all piece logic — including movement, capturing, and turns — using JavaScript and jQuery events.


---


## 🧱 Project Structure

📂 chess-game

├── index.html # Main HTML file — defines the chessboard and layout

├── style.css # Styling for board, cells, and neon effects

└── script.js # Game logic and move handling


---


## 🕹️ How to Play

1. Open the game in your browser.  
2. The board loads with pieces positioned at their standard starting places.  
3. Click on a piece to select it.  
4. Then click on a valid square to move it.  
5. The display at the bottom shows whose turn it is: **White** or **Black**.


> ♟️ Game alternates turns automatically after each valid move.


---


## ✨ Features


- ✅ **8×8 Chess Board** with coordinate labels (`a–h`, `1–8`)
- ✅ **Dynamic Gameplay** using JavaScript DOM updates  
- ✅ **Turn Indicator** – Displays “It’s White’s Turn” or “It’s Black’s Turn” dynamically  
- ✅ **Animated Hover Effects** – Squares glow with neon animation when hovered  
- ✅ **Responsive Design** – Board adjusts to different screen sizes  
- ✅ **Custom Neon CSS Effects** – Blue, orange, and green glow effects on text and cells  
- ✅ **Shake Animation** on hover for fun interaction  
- ✅ **Minimal Dependencies** – only uses jQuery for event handling 


---


## 🎨 Styling Highlights (`style.css`)


- `.gamecell`: Defines the look and feel of each cell (size, border, hover animation).
- `.grey`: Applies alternating dark squares for the chessboard pattern.
- `.neonblue_txt`, `.neongreen_txt`, `.neonorange_txt`: Add glowing animations using CSS keyframes.
- `.shake-little`: Adds a subtle shaking hover animation for interactivity.
- `#turn`: A live text box that updates dynamically to show whose move it is.


Example:
```css
.gamecell:hover {
  color: #f1ecec;
  background: rgba(37, 88, 228, 0.712);
  transform: translate(10px, -10px);
  animation: neonBlueText 1.5s ease-in-out infinite alternate;
}

```

⚙️ Logic Highlights (script.js)

- The JavaScript file (script.js) contains logic for:

- Initializing the chessboard and placing pieces.

- Handling player turns.

- Validating moves.

- Changing the display to show the current player’s turn.

- Managing click events on each square using jQuery ($('.gamecell').on('click', ...)).

- It updates the board dynamically each time a valid move is made.



💡 How It Works (Step by Step)

1. Board Creation:
The index.html file manually defines all 64 squares using <div> elements with alternating classes (grey and default white).

2. Styling:
The style.css adds grid-like visuals, shadows, and animations to make the board appear polished.

3. Logic Execution:
The script.js file detects which square a player clicks on, determines which piece to move, and then updates the board accordingly.

4. Turn Switching:
After each valid move, the turn automatically switches and updates the display with animation (turnhighlight effect).



🚀 Run Locally

You can run this game easily on your system:

1️⃣ Clone the repository :-  https://akashreddy-ops.github.io/CHESS-GAME/

2️⃣ Open the project folder :- cd javascript-chess-game

