## Spacex-Applied-Data-Science-Capstone
## SpaceX Launch Prediction: Applied Data Science Capstone

This project simulates a real-world data science role at a fictional company, **SpaceY**, competing with SpaceX. The objective was to predict whether the Falcon 9 rocket’s first stage would land successfully using public launch data and machine learning.

## Highlights

- Cleaned and merged data from the SpaceX API and Wikipedia
- Performed EDA using SQL queries, visualizations, and geospatial maps (Folium)
- Built an interactive dashboard with Plotly Dash
- Trained and evaluated multiple classifiers: Logistic Regression, SVM, KNN, and Decision Tree
- Best model: **Decision Tree**, with 94.4% accuracy and no false negatives

## Key Technologies

Python, Pandas, NumPy, SQL, Matplotlib, Seaborn, Scikit-learn, Plotly Dash, Folium, BeautifulSoup

## Project Structure

| File / Notebook | Description |
|-----------------|-------------|
| `1) API Data Collection.ipynb` | SpaceX API extraction |
| `2) Web Scraping.ipynb` | Wikipedia data extraction |
| `3) Data Wrangling.ipynb` | Data cleaning & feature engineering |
| `4) EDA SQL.ipynb` | SQL-based exploration |
| `5) EDA Data Visualization.ipynb` | Plots: payload, orbit, trends |
| `6) Interactive Visual Analytics with Folium.ipynb` | Launch site maps |
| `7) Interactive Visual Analytics Plotly.py` | Interactive dashboard |
| `8) Machine Learning Prediction lab.ipynb` | Classification model training & evaluation |

## Example Insights

- Launch success has increased significantly over time
- KSC LC-39A had the highest landing success rate
- Heavier payloads and certain orbits (e.g., GEO, ES-L1, SSO) showed consistent landing success
- All models reached ~83% accuracy, with Decision Tree performing best overall

## Running the Dashboard

1. Clone the repository:
```bash
git clone https://github.com/jovannagarza/Spacex-Applied-Data-Science-Capstone.git
cd Spacex-Applied-Data-Science-Capstone
pip install -r requirements.txt
python "7) Interactive Visual Analytics Plotly.py"

