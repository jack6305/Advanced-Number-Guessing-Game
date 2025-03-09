🎯 Advanced Number Guessing Game

📌 Overview  
The Advanced Number Guessing Game is an interactive Python-based game featuring single-player & multiplayer modes. It includes a hint system, leaderboard tracking, and performance monitoring to enhance user engagement and competitiveness.

🚀 Features  
✅ Single & Multiplayer Modes  
✅ Multiple Difficulty Levels (Easy, Medium, Hard)  
✅ Hints System (Even/Odd Hint every 3 incorrect guesses)  
✅ Leaderboard (JSON-based storage for high scores)  
✅ Time Tracking & Score Calculation  
✅ Input Validation & Error Handling  
✅ Clear & Structured Code for Easy Expansion  

📂 Project Structure  
Advanced-Number-Guessing-Game/  
├── game.py             Main game logic  
├── leaderboard.json    Stores high scores  
├── README.md           Project documentation  

🎮 How to Play  

Single Player Mode  
1. Select difficulty level:  
   - Easy (1-50, 10 attempts)  
   - Medium (1-100, 7 attempts)  
   - Hard (1-200, 5 attempts)  
2. The game will randomly select a number within the chosen range.  
3. Try to guess the number correctly within the given attempts.  
4. If you struggle, you can get hints (Even/Odd) every 3 incorrect guesses.  
5. The game will track your performance and update the leaderboard.  

Multiplayer Mode  
1. Player 1 selects a number (1-100) for Player 2 to guess.  
2. Player 2 has 7 attempts to find the correct number.  
3. The player who guesses correctly wins!  

🏆 Leaderboard System  
The game maintains a leaderboard using leaderboard.json.  
- Scores are based on the number of attempts taken.  
- The lower the score, the better the ranking.  
- The leaderboard automatically updates when a player wins.  

📜 Leaderboard Format (leaderboard.json):  
{
    "Player1": 50,
    "Player2": 30
}  

- If a new score is lower than the previous one, it updates the leaderboard.  

📥 Installation & Setup  

🔧 Requirements  
- Python 3.x  
- No external libraries needed (Pure Python Implementation)  

▶️ Run the Game  
1. Clone the repository:  
   git clone https://github.com/your-username/Advanced-Number-Guessing-Game.git  
2. Navigate to the project folder:  
   cd Advanced-Number-Guessing-Game  
3. Run the game:  
   python game.py  

⚙️ Game Mechanics  

1️⃣ Scoring System  
- Base score: 100  
- Every incorrect guess: -10 points  
- Using hints: -5 points per hint  
- Faster guesses result in higher scores!  

2️⃣ Hints System  
- After 3 incorrect guesses, you can request a hint.  
- The hint will tell you if the number is EVEN or ODD.  
- Using hints reduces your score.  

3️⃣ Input Validation  
- Only valid numbers within the chosen range are accepted.  
- Error handling ensures the game does not crash on invalid input.  

📜 Future Enhancements  

🚀 Planned Features for Future Versions:  
- GUI version using Tkinter/PyGame  
- Additional hint types (Higher/Lower Range, Divisibility)  
- Multiplayer Online Mode (via Sockets)  
- More Difficulty Levels  

🤝 Contribution  
Contributions are welcome! If you want to improve the game, follow these steps:  
1. Fork the repository  
2. Create a new branch (feature-improvement)  
3. Commit changes and push  
4. Submit a Pull Request  

📜 License  
This project is open-source under the MIT License.  

👨‍💻 Author  
KRISHNA  

