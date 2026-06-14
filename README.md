# Google Step Up Career Challenge — Data Science

**Organiser:** The Data Inspiration Group  
**Track:** Data Science  
**Certificate:** [View Certificate](#) 

---

## The Brief

Help Google plan a $10M multi-market campaign to drive Gemini Pro sign-ups among university students. The dataset contained brand lift studies across multiple markets and channels — the challenge was to figure out which results were actually meaningful before building any strategy on top of them.

---

## What I Did

### Step 1 — Statistical Validation
Most people treat statistical significance like a checkbox. I didn't.

Before touching any strategy, I built a Python pipeline to run proportion z-tests across every brand lift study in the dataset — separating genuine signal from noise. Studies that looked impressive on paper but didn't clear the significance threshold were flagged and excluded. Every insight built on top of unvalidated data is fiction.

### Step 2 — Cost Efficiency Analysis
Joined the validated lift data back to campaign spend to calculate **Cost Per Lifted User** across markets and channels — a metric that cuts through vanity numbers and shows where budget actually moves the needle.

### Step 3 — Strategic Recommendations
Used the validated, cost-adjusted data to identify:
- Which creatives genuinely moved consideration
- Which channels delivered the most efficient reach
- Which markets offered the best return on spend

---

## Key Learning

The field you apply data science in changes. The thinking doesn't. Statistical rigour isn't a step you do at the end — it's the foundation everything else is built on.

---

## Files
- `.ipynb` — full Python pipeline including z-tests, spend joins, and Cost Per Lifted User calculations
- `.pdf` — final strategic recommendations presented to the challenge

---

## Tech
- Python, Pandas, NumPy, SciPy
- Proportion z-tests
- Jupyter Notebook
