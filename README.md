Snake Game with Hand Tracking using Computer Vision

<img width="1154" alt="Screen Shot 2023-12-03 at 10 21 43 PM" src="https://github.com/AYoussef00/SNACK-GAME-Computer-Vision/assets/33284639/69a482c3-6f70-4da5-91f3-cc01a1c50e67">



Overview
This repository contains a snake game that is played using hand gestures captured through a camera. The game utilizes computer vision techniques to track hand movements, enabling users to control the snake's direction and interact with the game environment.

Features
Hand Tracking: The game employs the cvzone library for efficient hand tracking, allowing users to control the snake with their hand movements.

Dynamic Snake Length: The snake's length dynamically adjusts based on the distance covered, providing a challenging yet engaging gaming experience.

Score System: Users earn points by capturing food items with the snake, and the score is prominently displayed on the screen.

Game Over Handling: The game includes a robust game-over mechanism. Upon collision with the snake's own body, a clear "Game Over" message is displayed, along with the user's final score.

Getting Started

Clone the repository:

- git clone https://github.com/<your-username>/snake-game-hand-tracking.git
- cd snake-game-hand-tracking

Install dependencies:

- pip install -r requirements.txt

Run the game:

python snake_game.py

Requirements
Python 3.x
OpenCV
cvzone
Usage

Launch the game and use your hand gestures in front of the camera to control the snake.
Capture food items to increase your score.

Press 'r' to restart the game after a game over.

Contributing
Contributions are welcome! Feel free to open issues or pull requests for bug fixes, improvements, or new features.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
The game is built on the foundation of the cvzone library and OpenCV.
Special thanks to the contributors and the open-source community.
