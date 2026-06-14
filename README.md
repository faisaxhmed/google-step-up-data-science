# Google Step Up Career Challenge — Data Science

**Organiser:** The Data Inspiration Group  
**Track:** Data Science  
**Certificate:** [View Certificate](https://github.com/faisaxhmed/google-step-up-data-science/blob/main/Google%20Step%20Up%20Work%20Experience%20Certificate_cropped.pdf)

---

## The Brief

Help Google plan a $10M multi-market, 8-week digital campaign to drive Gemini Pro sign-ups among university students across 3 markets. The task was to analyse historic campaign performance and brand lift data to identify what had driven success with this audience, then translate those insights into a data-driven campaign strategy.

---

## What I Did

### Step 1 — Statistical Significance Testing
Before building any strategy, I validated which brand lift studies were genuinely meaningful. I built a Python pipeline using `statsmodels` to run proportion z-tests across all 48 brand lift studies, filtering down to 40 statistically significant results. The 8 studies that failed the threshold were excluded — building strategy on unvalidated lift data produces fiction, not insight.

### Step 2 — Historic Campaign Analysis
Analysed campaign performance across markets and channels to calculate CPA, CPM, and conversion rate. Identified which market and channel combinations drove the most efficient results historically.

### Step 3 — Cost Per Lifted User (CPLU)
Joined the validated brand lift data back to historic spend using a composite join key across Campaign, Market, and Channel. Calculated CPLU — spend divided by number of lifted users — to identify the most cost-efficient campaigns for influencing student consideration.

### Step 4 — Creative Analysis
Filtered creative performance data for the 18-24 target audience and ranked creatives by consideration lift across markets and channels.

---

## Key Findings
*Based on simulated datasets provided as part of the challenge.*

- Filtered 48 brand lift studies down to 40 statistically significant results — 8 studies were excluded for failing the significance threshold
- EG and SA Search delivered the lowest CPA at ~$3.23, compared to $120+ for UK and DE Display
- ExamPrep_23 on YouTube in SA achieved the lowest CPLU, making it the most cost-efficient campaign for influencing student consideration
- Display channels failed significance testing in most markets and should be deprioritised
- "Life Hack" creative drove the highest consideration lift among 18-24s — strongest in Germany via Social

---

## Files
- [`Notebook`](https://github.com/faisaxhmed/google-step-up-data-science/blob/main/Google%20Step%20Up%20Challenge%20Faisa%20Ahmed.ipynb) — full Python pipeline including z-tests, dataset joins, and CPLU calculations
- [`Presentation`](https://github.com/faisaxhmed/google-step-up-data-science/blob/main/Google%20Step%20Up%20Career%20Challenge.pptx) — final strategic recommendations

---

## Tech
- Python, Pandas, NumPy, SciPy, Statsmodels
- Proportion z-tests
- Jupyter Notebook
