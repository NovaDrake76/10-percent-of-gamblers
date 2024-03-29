This Python script simulates a modified Martingale betting strategy across different scenarios for a coin flip game, aiming to analyze the outcomes for a large number of players. The core idea behind the Martingale strategy is to double the bet after a loss, with modifications applied to manage risk and betting behavior. The script provides insights into the financial implications of using this strategy under varying conditions.

# Key Features:
Simulation of Modified Martingale Logic: The script simulates a coin flip game where players adjust their bets based on previous outcomes, following a modified Martingale strategy. The modifications include resetting the bet to a base value after a win, doubling the bet after a certain number of consecutive losses, and stopping the game if the loss streak exceeds a predefined threshold (X).

Multiple Scenarios: It runs simulations across three different modes, each with distinct parameters for the base bet, the loss streak threshold (X), and the number of games played. This allows for a comprehensive analysis of how different strategies perform over a large number of iterations.

Statistical Analysis: For each mode, the script calculates and displays statistics such as the number of players who ended up with a profit, the number of players who suffered a loss, the average profit for profitable players, the average loss for losing players, the best case scenario (highest balance achieved), and the chance of making a profit.

Loss Streak Visualization: It tracks and visualizes significant loss streaks (defined as 11 or more consecutive losses) within the simulation, highlighting these moments on the graph to provide a visual representation of risk points.

Outcome Visualization: Graphs are generated to show the balance progression of the first 100 players in each mode, offering a visual insight into how balances change over time and the impact of significant loss streaks.

# Use Cases:
Risk Analysis for Betting Strategies: By simulating different betting strategies and visualizing the outcomes, users can better understand the risks and potential rewards associated with the modified Martingale strategy.

Educational Tool: The script serves as an educational tool for understanding the principles behind betting strategies and the importance of managing risk and expectations.

Financial Planning for Gamblers: It provides gamblers with a data-driven analysis of how different betting strategies might perform, helping them to make more informed decisions.

# How It Works:
Simulation Setup: Users define the parameters for each simulation mode, including the base bet, the threshold for stopping the game after consecutive losses, and the number of games to be played.

Running Simulations: The script simulates the game for 1,000 players for each mode, applying the modified Martingale logic to adjust bets based on the outcomes of coin flips.

Analysis and Visualization: After running the simulations, the script analyzes the results to provide statistical insights and generates graphs to visualize the progression of player balances and highlight significant loss streaks.

This script is a powerful tool for analyzing the financial implications of betting strategies, offering both numerical and visual insights into the performance of the modified Martingale strategy under various conditions.

![image](https://github.com/NovaDrake76/10-percent-of-gamblers/assets/65428910/6caaa2f8-0e45-484e-905e-9ab796137b87)
