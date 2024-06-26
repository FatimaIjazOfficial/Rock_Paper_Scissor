### GitHub README

# Rock Paper Scissors Game

Welcome to the Rock Paper Scissors game! This is a simple Python implementation of the classic game where you can play against the computer.
This is a simple Rock, Paper, Scissors game implemented in Python. The game allows a user to play against the computer by choosing Rock, Paper, or Scissors. The computer randomly selects one of the three options, and the winner is determined based on the classic rules of the game.

### Code Description

The code starts by importing the `random` module to enable random selection for the computer's choice. The ASCII art representations of Rock, Paper, and Scissors are stored in variables for display purposes.

The user is prompted to enter their choice (0 for Rock, 1 for Paper, and 2 for Scissors). The computer then randomly selects its choice using `random.randint(0, 2)`.

Both the user's and the computer's choices are printed along with the corresponding ASCII art. The game then determines the winner based on the rules:

- Rock crushes Scissors
- Scissors cuts Paper
- Paper covers Rock

If both the user and the computer make the same choice, the game results in a tie.
## How to Play

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/rock-paper-scissors.git
   cd rock-paper-scissors
   ```

2. **Run the game**:
   ```bash
   python rock_paper_scissors.py
   ```

3. **Make your choice**:
   - Enter `0` for Rock
   - Enter `1` for Paper
   - Enter `2` for Scissors

4. **See the result**:
   - The game will display your choice and the computer's choice with ASCII art.
   - The result (win, lose, or tie) will be printed.

## Example Output

```
What do you choose : (0)Rock (1)Paper (2)Scissors ? 1
Me : Paper
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)

Computer : Rock
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)

You Win
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README as needed!
