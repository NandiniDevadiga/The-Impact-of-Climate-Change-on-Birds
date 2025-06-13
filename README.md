# 🐦 The Impact of Climate Change on Birds

This project explores how climate variables such as temperature and humidity affect bird sightings over the past four decades. We use a synthetic dataset and apply Logistic Regression to classify bird species based on environmental conditions. The project also includes an interactive map to visualize bird sightings across locations in India.

---

## 📊 Objective

- Analyze the relationship between bird sightings and climate changes.
- Build a Logistic Regression model to classify bird species.
- Visualize trends and sightings on a map using Folium.

---

## 📦 Technologies Used

- Python
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- folium (for map visualization)
- Jupyter Notebook

---

## 📌 Key Steps

1. Load and explore the dataset.
2. Encode categorical variables and scale features.
3. Train a Logistic Regression model.
4. Evaluate model performance using classification report.
5. Visualize climate trends using line plots.
6. Map bird sightings using an interactive `folium` map.

---

## 🧪 Model Used

**Logistic Regression** (with scaled features and `saga` solver to avoid convergence issues)

---

## 🗺️ Map Preview

Bird sightings are visualized using [folium](https://python-visualization.github.io/folium/). The map includes clustered markers for each sighting with species name, year, and number of sightings.

✅ Output saved as `bird_sightings_map.html`.

---

## 📁 Dataset

A synthetic dataset of 500 records was generated with the following fields:
- `species`: Bird species name
- `sightings`: Count of sightings
- `avg_temp`: Average temperature
- `humidity`: Humidity level
- `location_lat`, `location_long`: Latitude and longitude
- `year`: Year of observation

---

## 🧠 Future Work (Optional Extensions)

- Add pseudo-absence data for binary classification
- Use Random Forest or XGBoost for better performance
- Incorporate real-world bird and climate datasets
- Deploy as a streamlit dashboard or Flask app

---

## 📎 How to Run

1. Clone the repo
2. Open the Jupyter notebook `birds_climate_analysis.ipynb`
3. Run all cells
4. Open `bird_sightings_map.html` in your browser to view the map

---

## 🔗 License

This project is for educational purposes only.
