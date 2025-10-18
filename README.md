# Team Effectiveness: Home vs Away (NBA 2024)

### Overview
This project explores whether NBA teams perform differently at home versus away.  
Using 2024 play-by-play and matchup data, we analyzed field-goal efficiency, shot-type mix, substitutions, free-throw accuracy, scoring runs, win rate, and turnovers.

### Contributors
Kang Ni, Stephanie Chen, Marcus Shi, Bill Odiase, Steven Marathias, Keane Albright (Project Manager)

### Project Structure (Inside the Notebook)
- Executive Summary - Final: High-level findings and implications.
- Project Motivation & Data Overview: Problem framing, data sources, and context.
- Summary of Team Assignment Phase: What carried over and what changed in the final.
    - Final Submission Phase (Analyses):
    - Player & Team Efficiency
    - First Few Minutes & Clutch Time
    - Home vs. Away Win Rate
    - Foul Rate & Free Throw Success by Quarter
    - Field Goal Trends: Home vs. Away Efficiency & Shot Patterns
    - Average Home vs. Away Scoring & % Home Wins
    - Scoring Runs & Average Time in the Lead
    - Turnover Differential at Home vs. Away
- Conclusion - Final: Synthesis and recommendations.
- GenAI Disclosure & Appendix

### Key Insights
- **Shooting:** Home teams shoot *slightly* better-especially at the rim and from three-but strategy stays constant.  
- **Shot Mix:** Similar 2-pt / 3-pt distribution regardless of venue.  
- **Substitutions:** Rotation timing is consistent home and away.  
- **Free Throws:** No evidence of a systematic home-court bias.  
- **Momentum Runs:** Long scoring streaks happen equally in both contexts.  
- **Scoring & Wins:** Home sides average marginally more points and wins.  
- **Turnovers:** Venue effects vary by team; not league-wide.

### File Structure
```
.
├── README.md
├── B07-Team-Effectiveness-Home-v-Away-Final-Submission.ipynb
├── data/
│   ├── matchups_2024.csv
│   └── cdnnba_2024.csv
├── figures/          # optional chart exports
├── requirements.txt  # optional
└── .gitignore
```

### Environment Setup
```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```
Example `requirements.txt`:
```
pandas
numpy
matplotlib
seaborn
plotly
scipy
scikit-learn
```

### Running the Notebook
1. Place both CSVs in the `data/` folder.  
2. Launch Jupyter Lab or Notebook.  
3. Open `B07-Team-Effectiveness-Home-v-Away-Final-Submission.ipynb`.  
4. Choose **Kernel - Restart & Run All** to reproduce all charts and tables.

### Data Sources
- **matchups_2024.csv** - team and venue metadata  
- **cdnnba_2024.csv** - play-by-play actions and scores  

### Limitations Results Summary
Home-court advantage exists but is modest: efficiency improves slightly, yet team style and momentum remain stable. The advantage is more psychological than structural.

### Acknowledgments
Boston University MSBA BA780 - Intro to Data Analytics.  
Python scientific-stack and open NBA datasets.

### Generative AI Disclosure
ChatGPT / GitHub Copilot assisted with markdown editing and minor Pandas syntax.  
All code, results, and interpretations were validated by the team.
