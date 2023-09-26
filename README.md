# Games_Python

# Detective Game

Welcome to the Detective Game, a text-based murder mystery game written in Python. In this game, you play the role of a detective trying to solve a murder mystery by questioning suspects, inspecting the crime scene, and making accusations.

## How to Play

1. **Introduction**: 
    - You are a detective tasked with solving a murder mystery.
    - The victim's identity and the murder weapon are randomly generated at the beginning of the game.
    - You have a list of suspects; one of them is the murderer, but you don't know who.
    - Your goal is to identify the murderer and the murder weapon.

2. **Game Loop**:
    - The game operates in a loop where you can choose from the following options:
        - **Question a Suspect**: You can question a randomly chosen suspect. The suspect may act nervously or have an alibi.
        - **Inspect the Crime Scene**: You can inspect the crime scene and discover clues, such as the murder weapon and other evidence.
        - **Make an Accusation**: When you think you've gathered enough evidence, you can make an accusation by specifying a suspect and a murder weapon.
        - **Quit**: You can quit the game at any time.

3. **Winning the Game**:
    - To win the game, you must make a correct accusation by naming both the murderer and the murder weapon.
    - If your accusation is correct, you've solved the case and captured the murderer.
    - If your accusation is incorrect, the murderer remains at large.

## Customize and Expand

This is a basic framework for a detective game, and you can expand upon it to create a more engaging experience. Here are some ideas for customization and expansion:

- **Add More Characters**: Increase the number of suspects to make the game more challenging.
- **Enhance Clues**: Create a variety of clues that the player can discover during the game.
- **Create a Storyline**: Develop a storyline that adds depth and context to the murder mystery.
- **Graphics**: Consider adding ASCII art or basic graphics to enhance the game's visuals.
- **Difficulty Levels**: Implement different difficulty levels with varying levels of complexity.
- **Save and Load**: Allow players to save and load their progress in the game.
- **Sound and Music**: Incorporate sound effects and background music to improve the gaming experience.

## Getting Started

1. Make sure you have Python installed on your computer.

2. Download the `detective_game.py` file.

3. Open your terminal or command prompt and navigate to the directory where the `detective_game.py` file is located.

4. Run the game by executing the following command:
    ```
    python detective_game.py
    ```

5. Follow the on-screen instructions to play the game.

Enjoy the Detective Game and put your detective skills to the test! Can you solve the mystery?

# Mario Kart-inspired Racing Game

Welcome to the Mario Kart-inspired Racing Game! This is a simplified text-based racing game where you control a character and race against computer-controlled opponents on a track.

## How to Play

1. **Game Objective**:
    - The objective of the game is to reach the end of the track (defined by `track_length`) before your opponents do.

2. **Characters**:
    - You play as Mario, while there are three computer-controlled opponents: Luigi, Yoshi, and Toad.
    - Each character has a speed and acceleration value, affecting their progress in each turn.

3. **Game Loop**:
    - The game operates in a loop where each turn consists of the following:
        - Your character's turn: Your character's speed and acceleration are used to determine your progress in this turn.
        - Opponents' turns: The computer-controlled opponents' speed and acceleration are used to determine their progress.
        - Display of race progress: The game displays the race progress using '=' characters on the console.

4. **Winning the Game**:
    - The game continues until either you or one of the opponents reaches the end of the track (defined by `track_length`).
    - If you reach the end of the track first, you win the race.

5. **End of the Game**:
    - When the game ends, whether you win or lose, it will display a message to thank you for playing.

## Customize and Expand

This is a basic framework for a racing game, and you can expand upon it to create a more immersive and interactive experience. Here are some ideas for customization and expansion:

- **Graphics**: Consider using a game development framework like Pygame or Unity to add graphical elements and make the game visually appealing.
- **More Characters**: Add more characters with unique abilities, and let players choose their character.
- **Power-Ups**: Implement power-ups and items inspired by Mario Kart to enhance gameplay.
- **Multiple Tracks**: Create multiple race tracks with varying difficulty levels.
- **Player Interaction**: Add player interaction such as steering, using items, or drifting during races.
- **Sound and Music**: Incorporate sound effects and background music to improve the gaming experience.

## Getting Started

1. Make sure you have Python installed on your computer.

2. Download the `mario_kart_game.py` file.

3. Open your terminal or command prompt and navigate to the directory where the `mario_kart_game.py` file is located.

4. Run the game by executing the following command:
    ```
    python mario_kart_game.py
    ```

5. Use the game controls to progress through the race and aim to reach the end of the track before your opponents.

Enjoy the Mario Kart-inspired Racing Game and have fun racing against the computer-controlled opponents!

# Number Guessing Game

The Number Guessing Game is a simple Python-based game where the player attempts to guess a randomly generated number within a limited number of attempts. The game provides feedback to help the player refine their guess.

## How to Play

1. Run the `number_guessing_game.py` script by executing the following command in your terminal or command prompt:


2. The computer will select a random number between 1 and 100 as the secret number.

3. You will have a maximum of 10 attempts to guess the secret number.

4. Enter your guess when prompted.

5. After each guess, the game will provide feedback, letting you know if your guess is too high or too low.

6. Keep guessing until you either guess the correct number or run out of attempts.

7. The game will display a message with the number of attempts it took to guess the correct number or inform you that you've run out of attempts.

## Example

Welcome to the Number Guessing Game!
I'm thinking of a number between 1 and 100. You have 10 attempts to guess it.
Enter your guess: 50
Too low. Try again.
Enter your guess: 75
Too high. Try again.
Enter your guess: 60
Too low. Try again.
Enter your guess: 70
Congratulations! You guessed the number 70 correctly in 4 attempts.

## Customization

You can customize the game by modifying the following parameters in the `number_guessing_game.py` script:

- Change the range of numbers: Modify the arguments of `random.randint()` to select a different range.
- Adjust the maximum number of attempts: Modify the `max_attempts` variable to set a different limit on the number of guesses.

## Author

bequbed

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



