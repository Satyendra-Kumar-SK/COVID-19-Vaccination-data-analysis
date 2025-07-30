# COVID-19-Vaccination-data-analysis
A Jupyter Notebook exploring global COVID-19 vaccination trends, efficacy, and impact on case rates
🧬 COVID-19 Vaccine Analysis Notebook
This project is a data-driven exploration of COVID-19 vaccination trends, vaccine efficacy, and their relationship to case counts. The analysis is performed in a single, well-organized Jupyter Notebook, complete with visualizations, code, and commentary.

📂 Notebook file: covid19_vaccine_analysis.ipynb
🧪 Tools used: Pandas, Matplotlib, Seaborn
📊 Data sources: Public datasets from Our World in Data, simulated VAERS, and example efficacy tables.
📌 What's Inside
The notebook walks you through several important aspects of COVID-19 vaccine data. Each section is self-contained, explained, and visualized.

1. 🌍 Vaccine Distribution by Country
Objective: Compare total vaccinations across countries (latest available date).

Data: vaccinations.csv from Our World in Data.

Output: Bar chart showing top 10 countries by total administered doses.

2. 📈 Vaccination Progress Over Time
Objective: Track how vaccination rates have changed over time in a specific country.

Default country: United States (modifiable).

Metrics: People vaccinated per 100, fully vaccinated per 100.

Output: Line chart showing trends over time.

3. 🧪 Vaccine Efficacy (Against Variants)
Objective: Visualize how effective different vaccines are against COVID-19 variants.

Data: Simulated sample of vaccine efficacy from literature.

Variants included: Alpha, Delta.

Output: Grouped bar chart comparing vaccine efficacy by variant.

Real-world efficacy data often comes from published studies and may need manual extraction or scraping.

4.  Adverse Events (Side Effects) by Vaccine
Objective: Summarize reported side effects by vaccine type.

Data: Example dataset simulating VAERS-type reporting.

Output: Bar chart showing number of side effect reports by vaccine.

Note: For real analysis, use publicly available VAERS data and apply preprocessing filters.

5. 🔗 Correlation: Vaccination vs COVID-19 Cases
Objective: Explore how vaccination rates relate to COVID-19 case numbers.

Approach:

Merge vaccination and case data for a single country.

Plot both over time.

Calculate Pearson correlation between full vaccination rate and new daily cases.

Output: Line chart + printed correlation coefficient.

🛠️ How to Use
Download the file covid19_vaccine_analysis.ipynb.

Open in Jupyter Lab or Jupyter Notebook.

Run the notebook cells sequentially, or explore specific sections as needed.

You’ll need Python installed with the following libraries:
pip install pandas matplotlib seaborn

📊 Data Sources
Dataset	Source
Vaccination & Case Data	Our World in Data
Adverse Events (Simulated)	Based on patterns from VAERS
Efficacy Data (Example)	Based on published research summaries
Disclaimers
Example data for efficacy and side effects is for illustrative purposes only.

This analysis is intended for educational and exploratory use — not medical decision-making.

🧠 Summary of Insights
Clear global leaders in vaccine distribution.

Noticeable time trends in vaccination rollout by country.

Vaccine efficacy varies by manufacturer and variant.

Adverse event patterns differ across vaccines.

In some cases, a negative correlation between vaccination rates and new case counts is observed — suggesting vaccines help reduce transmission.

📄 License
This project is released under the MIT License. See LICENSE for details.
