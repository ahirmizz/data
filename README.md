# La Liga Season Team Stats Dataset

This dataset contains aggregated team-level statistics for each La Liga season (2019–2025).  
The data was collected from [football-data.co.uk](https://www.football-data.co.uk/) and processed into a clean, season-level format for machine learning experiments.  

## File: `laliga-season-team-stats.csv`

**Columns:**
- `Season` → The season year (2019–2025)
- `Team` → Club name
- `GoalsScored` → Total goals scored in the season
- `GoalsConceded` → Total goals conceded
- `Shots` → Total shots
- `Fouls` → Total fouls committed
- `Corners` → Total corners
- `YellowCards` → Yellow cards received
- `RedCards` → Red cards received
- `Wins` → Matches won in the season

**Usage:**
- Train machine learning models to predict league performance
- Analyze season trends across teams
- Feature engineering for match-level or season-level predictions
