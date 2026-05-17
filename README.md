🏏 IPL Crunch '26 — Data Analysis

Wooble IPL Crunch '26 | Online Data Analytics Challenge | May 2026


👤 Analyst
Rakesh Kalisetty
Data Analyst | IPL Crunch '26 Participant

📌 About This Project
Everyone has IPL opinions. Very few can back them with data.
This project is my submission for Wooble's IPL Crunch '26 — an online data analytics challenge where participants work with real ball-by-ball IPL datasets to uncover patterns, answer high-impact cricket questions, and present insights through charts, analysis, and storytelling.
I analyzed 13 seasons of IPL data (2008–2020) covering 816 matches and 179,078 deliveries to answer questions that go beyond the surface level of cricket statistics.

📂 Repository Structure
ipl-crunch-26/
│
├── IPL_Crunch_26_Analysis.ipynb        # Complete Python analysis notebook (Google Colab)
├── IPL_Crunch_26_Rakesh_Kalisetty.pdf  # Full analysis report (PDF format)
├── IPL_Crunch_26_Rakesh_Kalisetty.pptx # Presentation slides (PPT format)
└── README.md                           # Project overview (this file)

📊 Dataset
SourceFormatSeasonsKaggle — IPL Complete DatasetCSV (matches + deliveries)2008 – 2020

matches.csv — 816 matches with toss, result, venue, teams data
deliveries.csv — 179,078 ball-by-ball delivery records


🔍 Analyses Performed
1. 🎯 Does Winning the Toss Win the Match?
Analyzed toss outcomes vs match results across all seasons and teams.
Finding: Toss winners win only ~52% of matches — barely above a coin flip.
2. ⚡ Which Phase Impacts Victory Most?
Compared Powerplay (1–6), Middle Overs (7–15), and Death Overs (16–20) by run rate and wickets.
Finding: Powerplay wickets are the most decisive — early collapses almost always lead to a loss.
3. 🏏 Top Batters Across Seasons
Aggregated total runs, strike rates, boundaries, and Orange Cap winners by season.
Finding: Elite batters balance high run volume with strong strike rates — not just one.
4. 🎳 Top Bowlers Across Seasons
Aggregated wickets, economy rates, and Purple Cap winners by season.
Finding: Economy rate is a better measure of bowling quality than raw wicket count.
5. 🔍 Surprise Insight — The Chasing Advantage
Discovered a consistent and growing pattern across all IPL seasons.
Finding: Teams batting second (chasing) win 55–60% of the time. Captains have increasingly chosen to field first — a trend that has grown season by season due to dew factor, pitch deterioration, and psychological pressure on the batting side.
6. 🏟️ Bonus — Venue Analysis
Classified grounds as batter-friendly or bowler-friendly based on average runs per delivery.
Finding: Chinnaswamy (Bengaluru) heavily favours batters; Chepauk (Chennai) favours bowlers.

🛠️ Tools & Technologies
ToolPurposePython 3Core analysis languagePandasData cleaning & manipulationMatplotlibChart creationSeabornStatistical visualizationsGoogle ColabNotebook environment

💡 Key Takeaways

Toss is overrated — ~52% win rate after winning toss is barely better than random
Chase to win — fielding first after winning toss is the smarter strategic decision
Powerplay wickets are decisive — protect your top order in overs 1–6
Balance beats volume — elite batters combine runs AND strike rate
Economy > wickets — sustained bowling economy wins more games
Venue changes everything — ground conditions are an underutilised factor


🚀 How to Run the Notebook

Open Google Colab: https://colab.research.google.com/drive/1qV9vbhTaISrn9F7rqR7qszDA8rt88jF8?usp=sharing
Upload IPL_Crunch_26_Analysis.ipynb
Get a Kaggle API key from kaggle.com → Settings → Create Legacy API Key
Run Cell 1 → upload kaggle.json when prompted
Run all remaining cells top to bottom
All 6 charts auto-download as a ZIP at the end


🏆 Challenge Details
DetailInfoChallengeIPL Crunch '26OrganiserWoobleFormatIndividual ParticipationSubmission Deadline28 May 2026Prize Pool₹3,000

📜 Rules Followed

✅ Original work only
✅ AI tools used for assistance — all interpretation and analysis is my own
✅ Single submission
✅ Real IPL dataset used


Made with 🏏 and 📊 by Rakesh Kalisetty | Wooble IPL Crunch '26
