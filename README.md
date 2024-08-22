T20 International
Cricket Player Performance Analysis

This project analyzes cricket player performance by visualizing key metrics such as Strike Rate, Average Runs, and the number of centuries scored. The visualizations help in comparing players and understanding their performance trends.

Project Overview

The project involves the following key components:
- Data preprocessing and cleaning.
- Visualizations to compare cricket players' performance.
- Metrics analyzed include Strike Rate (SR), Average Runs (Ave), and the number of centuries scored.

Data

The dataset includes cricket player statistics with the following columns:
- `Player`: Name of the player.
- `Runs`: Total runs scored.
- `HS`: Highest score.
- `Ave`: Batting average.
- `SR`: Strike rate.
- `100`: Number of centuries scored.
- `50`: Number of half-centuries scored.
- Additional columns for boundary counts and other stats.

Visualizations

### 1. Pie Charts
Pie charts display the run distribution for individual players based on centuries, half-centuries, and other runs.

### 2. Bubble Chart
A scatter plot where:
- **X-axis**: Strike Rate (SR)
- **Y-axis**: Average Runs (Ave)
- **Bubble Size**: Number of Centuries (scaled for visualization)
- **Color**: Player

The bubble chart compares the top 15 players based on their total runs.
### 3. Bar Chart
Used for visualization many other parts

## Requirements

To run this project, you need:
- Python 3.x
- Required libraries: `pandas`, `matplotlib`, `seaborn`
