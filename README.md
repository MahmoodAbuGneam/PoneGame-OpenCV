
# Hand Tracking Pong Game

This project is a modern twist on the classic Pong game using OpenCV for hand tracking. The game detects your hands and fingers, distinguishing between the left and right hands. Your left hand's index finger controls the left paddle, and the right hand controls the right paddle, bouncing a basketball back and forth.

## Features
- **Hand tracking**: Detects and tracks both hands and their respective fingers using OpenCV and cvzone's HandTrackingModule.
- **Pong game mechanics**: The game works like the classic Pong, with a ball bouncing between two paddles that are controlled by the player's hands.
- **Real-time interaction**: Seamless, responsive controls and game mechanics based on real-time hand detection.

## Technologies Used
- **OpenCV**: For real-time video capture and image processing.
- **cvzone HandTrackingModule**: For detecting hands and fingers, and distinguishing between the left and right hand.
- **NumPy**: For array manipulation and computations.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/MahmoodAbuGneam/PoneGame-OpenCV
    ```
2. Install the required dependencies:
    ```bash
    pip install opencv-python cvzone numpy
    ```
3. Run the game:
    ```bash
    python PoneGame.py
    ```

## How It Works
- The game captures real-time video from your webcam and tracks both hands using `cvzone.HandTrackingModule`.
- The left hand's index finger controls the left paddle, and the right hand's index finger controls the right paddle.
- A basketball moves between the two paddles, and the player’s goal is to keep the ball bouncing.

## Screenshots
- *Game Over Screen*
![Game Over](./Resources/gameOver.png)

- *Pong Game in Action*
![Game in Action](./Resources/Background.png)

## Future Improvements
- Add support for multiplayer mode.
- Integrate sound effects and scoring systems.
- Improve hand tracking under various lighting conditions.

## Credits
Developed by Mahmood Gneam using OpenCV and cvzone. 

## License
This project is licensed under the MIT License.
