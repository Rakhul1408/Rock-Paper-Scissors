# Rock, Paper, Scissors Game

## Description
This is a simple command-line implementation of the classic game **Rock, Paper, Scissors** where you play against the computer. The game tracks scores and continues until the player decides to quit.

## How to Play
1. Run the program in a Python-supported environment.
2. Input your choice from `rock`, `paper`, or `scissors` when prompted.
3. The computer will randomly select its choice.
4. The game will determine the winner of the round and update the scores accordingly.
5. Type `quit` anytime to exit the game.

## Rules
- **Rock** beats **Scissors**.
- **Paper** beats **Rock**.
- **Scissors** beat **Paper**.
- If both you and the computer choose the same, it's a tie.

## Prerequisites
- Python 3.x installed on your system.

## How to Run the Program
1. Clone this repository or copy the `rock_paper_scissors.py` file to your local machine.
2. Open a terminal or command prompt.
3. Navigate to the directory containing the script.
4. Run the script using the command:
   ```bash
   python rock_paper_scissors.py
   ```
5. Follow the on-screen instructions to play.

## Example Gameplay
```
Welcome to Rock, Paper, Scissors!
Enter your choice (rock, paper, scissors or 'quit' to exit): rock
Computer chose: scissors
You win this round!
Scores - You: 1, Computer: 0

Enter your choice (rock, paper, scissors or 'quit' to exit): paper
Computer chose: rock
You win this round!
Scores - You: 2, Computer: 0

Enter your choice (rock, paper, scissors or 'quit' to exit): quit
Thanks for playing!
```

## Files
- `rock_paper_scissors.py`: The main game script.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Inspired by the classic game Rock, Paper, Scissors.
- Random choice generation using Python's `random` module.
