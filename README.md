# Academic Data Science & Engineering Coursework

This repository serves as a centralized portfolio for laboratory assignments, foundational programming scripts, and technical coursework completed during my professional development and academic training tracks.

## Repository Structure
- **`web_scraping_beautifulsoup_lab.ipynb`**: IBM Developer Skills Network lab covering programmatic data extraction out of nested HTML structures, tag tree navigation, and parsing web tables into structured Pandas DataFrames using `BeautifulSoup` and `requests`.

- **`time_series_trend_forecasting.ipynb`**: Implements dynamic time-series trend extraction and forecasting models over transactional log data. Utilizes `DeterministicProcess` to initialize deterministic time dummies, calculates rolling 365-day moving averages, and deploys Scikit-Learn `LinearRegression` frameworks to compute out-of-sample forward-looking trend projections.


## Core Technical Skills Demonstrated
- **Deterministic Trend Engineering:** Utilized `DeterministicProcess` frameworks to programmatically build time-dependency dummies, handling intercept biases (`const`) and linear order slopes to capture structural, long-term secular trends in historical datasets.
- **Rolling Window Signal Processing:** Deployed advanced rolling window calculations (`.rolling().mean()`) to compute centered 365-day moving averages, safely managing missing boundary periods (`min_periods`) to smoothly isolate long-term trends from localized seasonal noise.
- **Out-of-Sample Forecasting Pipelines:** Structured a complete forward-looking predictive pipeline using Scikit-Learn's `LinearRegression` engine, leveraging in-sample training features to project mathematical trend trajectories across future time-horizons.
- **Time-Series Index Manipulations:** Practiced sophisticated temporal data alignment within Pandas, parsing raw date-strings into structured time indices and mapping periodic frequency bounds (`.to_period()`) to maintain matrix alignment during comparative forecasting loops.

- **Automated Data Ingestion:** Extracting raw data from web architectures into Python memory stacks.
- **HTML DOM Parsing:** Navigating elements, siblings, parents, and attributes programmatically.
- **Data Rectification:** Restructuring raw HTML string blocks into clean, structured analysis tables.
