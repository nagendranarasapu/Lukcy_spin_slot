# Lukcy_spin_slot
This is Lucy Spin Slot end to end project

This Python code creates a simple slot machine game with the following key points:

1. Player Interaction: The player deposits money, selects the number of lines to bet on (1-3), and places a bet per line (within a defined range). The total bet is subtracted from the player's balance, and winnings are calculated based on matching symbols on the chosen lines.

2. Game Logic: The slot machine generates random symbols on a 3x3 grid based on predefined symbol counts and values. If the symbols on a selected line match across all columns, the player wins an amount calculated by multiplying the symbol's value by the bet.

The game loops, allowing players to continue spinning and adjusting bets until they choose to quit or their balance reaches zero. The game dynamically updates the player's balance after each spin based on their winnings or losses.

