# 🎰 Python Slot Machine Game

This is a command-line slot machine game built in Python. It simulates a simple 3x3 slot machine with symbols A, B, C, and D, each having different probabilities and payout values. The player can deposit money, place bets on up to 3 lines, and spin the machine to try their luck.

---

## 📂 Project Structure

- `main()` — Entry point of the program.
- `deposit()` — Asks the user how much money they want to deposit.
- `get_number_of_lines()` — Asks the user how many lines they want to bet on (1–3).
- `get_bet()` — Asks the user how much they want to bet per line.
- `get_slot_machine_spin()` — Randomly generates slot symbols based on symbol weights.
- `check_winnings()` — Checks if the user has won based on matching lines.
- `print_slot_machine()` — Displays the slot machine outcome in a 3x3 format.
- `spin()` — Coordinates the betting and spinning logic.

---

## 🧠 How the Game Works

1. **Deposit**: The user starts by depositing a certain amount of money.
2. **Bet**: The user chooses how many lines to bet on (up to 3) and how much to bet per line.
3. **Spin**: The slot machine generates random symbols based on predefined symbol frequencies.
4. **Payout**: If all symbols in a selected line match, the player wins a payout based on the symbol’s value.
5. **Repeat**: The user can continue playing until they run out of money or choose to quit.

---

## 💡 Slot Symbols & Values

| Symbol | Count (Weight) | Value (Multiplier) |
|--------|----------------|---------------------|
| A      | 2              | 5                   |
| B      | 4              | 4                   |
| C      | 6              | 3                   |
| D      | 8              | 2                   |

- Symbols with higher values are less likely to appear.
- Winning a line pays: `symbol value * bet amount`.

---

## 💻 Requirements

- Python 3.x

No external libraries are required. All functionality is built using Python's standard library (`random`, `input`, `print`, etc.).

---

## 🚀 Running the Game

To play the game, simply run the following command in your terminal:

```bash
python slot_machine.py
