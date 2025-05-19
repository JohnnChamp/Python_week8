**Project Title:**
COVID-19 Comparative Analysis: Cases, Testing, Deaths, Vaccinations & Policy Responses

---

### Short Description

A time-series analysis comparing Kenya, the United States, and India across key COVID-19 metrics—total and new cases, testing rates, deaths, vaccination rollouts, and government stringency measures—to uncover patterns, correlations, and policy impacts over the course of the pandemic.

---

### Objectives

* **Compare case trajectories** across three countries and identify which experienced the steepest growth and when.
* **Assess testing intensity** by examining new tests per thousand population (smoothed) as a proxy for surveillance effort.
* **Analyze mortality patterns** by tracking total deaths and death‐rate evolution over time.
* **Evaluate vaccination rollouts** via total vaccinations and estimated people vaccinated.
* **Examine policy responses** using the Oxford stringency index to see how government measures aligned with epidemiological trends.

---

### Tools & Libraries Used

* **Python 3.x**
* **pandas** for data cleaning, filtering, grouping, and forward-filling missing values
* **matplotlib & seaborn** for static visualizations (line plots, scatter plots)
* **Plotly Express** for interactive choropleth mapping
* **JupyterLab/Notebook** as the development environment

---

### How to Run / View the Project

1. **Clone the repository** (or download the notebook):

   ```bash
   git clone <repo-url>
   cd myproject
   ```
2. **Install dependencies** (preferably in a virtual environment):

   ```bash
   pip install pandas matplotlib seaborn plotly jupyterlab
   ```
3. **Launch JupyterLab**:

   ```bash
   jupyter lab
   ```
4. **Open `myproject.ipynb`**, run all cells in order, and explore the generated static and interactive plots.

---

### Insights & Reflections

* The United States exhibited the **steepest case and death curves**, while Kenya’s totals remained lower but may reflect under-testing.
* India’s **testing ramp-up** was most aggressive during its major waves, helping identify surges more clearly.
* **Vaccination rollouts** accelerated rapidly in the U.S. and India but lagged in Kenya, highlighting global disparities in supply and distribution.
* **Policy stringency** peaked in response to surges across all three countries, with India showing the sharpest climb and Kenya the most gradual adjustments—underscoring differences in governance capacity and public compliance.
* Forward-filling numeric gaps and grouping by country proved essential for clean time-series alignment; future work could integrate mobility data or variant prevalence for deeper causal insights.
