# Steam Games Keystone — Data Analysis

A look at 10,000 Steam games to see whether anything in the data, such as price, ownership volume,  
concurrent users, etc., correlate positively with player perception of a game.

## The Data

10,000 Steam game records pulled from a single dataset. Fields cover review counts, ownership  
estimates, pricing, playtime averages, development and publishing info, and peak concurrent users.  
Ownership is reported as a bucketed range rather than an exact figure, which is worth keeping in  
mind when reading anything derived from it.

## What I Was Looking At

- How user satisfaction scores are distributed across reviewed games
- Whether price has any relationship with review scores
- Whether ownership volume or concurrent users tell us anything about satisfaction trends

## What the Data Actually Said

Reviewed games trend positive with most sitting above 70%, though this ambiguous relationship  
did not make a clear suggestion regarding either the player base or the game quality. Price  
turned out to have no suggested impact on the user satisfaction scores. Satisfaction scores are  
consistent across every tier from free-to-play titles up to game over $60. The ownership and  
concurrent user analysis didn't reveal a clear connection either, though mid-range ownership  
titles tend to score slightly better than the outliers at either end.

## Structure

    data/               raw dataset
    notebooks/          full analysis notebook
    visualizations/     exported charts
    requirements.txt    dependencies
    README.md

## Setup

1. Clone the repository
2. Create and activate a virtual environment
3. `pip install -r requirements.txt`
4. Open `notebooks/keystone.ipynb` in Jupyter
5. Run all code
