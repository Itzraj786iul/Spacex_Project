# SpaceX Falcon 9 Landing Prediction

IBM Applied Data Science Capstone project by **Itzraj786iul**.

**Repository:** https://github.com/Itzraj786iul/Spacex_Project

## Project goal

Predict whether the SpaceX Falcon 9 first stage will land successfully, using public launch data, SQL/EDA, interactive analytics, and machine learning classification.

## Repository contents

| File | Description |
|------|-------------|
| `01-data-collection-api.ipynb` | Collect SpaceX launch data via REST API |
| `01-data-collection-webscraping.ipynb` | Scrape Falcon 9 launch records from Wikipedia |
| `01-data-wrangling.ipynb` | Clean data and create Class labels |
| `02-eda-sql.ipynb` | Exploratory analysis with SQL (SQLite) |
| `02-eda-dataviz.ipynb` | EDA with Matplotlib / Seaborn visualizations |
| `03-folium-map.ipynb` | Interactive Folium maps of launch sites |
| `03-dash-app.py` | Plotly Dash interactive dashboard |
| `04-predictive-models.ipynb` | Classification models (LR, SVM, Tree, KNN) |
| `spacex_launch_dash.csv` | Dataset used by the Dash app |
| `Data Science Capstone Project Report.pdf` | Final submission report (PDF) |
| `WinningSpaceRaceWithDataScience.pptx` | Final presentation (PowerPoint) |

## How to run the Dash app

```bash
pip install dash pandas plotly
python 03-dash-app.py
```

Then open the local URL shown in the terminal (usually `http://127.0.0.1:8050`).

## Key findings

- Launch success rate improved over time
- **KSC LC-39A** has the highest success rate among launch sites
- Launch sites are near the coast and relatively close to the equator
- Lower payload mass often shows better landing success
- **Decision Tree** performed best among the tested classifiers

## Author

- **Itzraj786iul**
- Date: July 24th, 2026
