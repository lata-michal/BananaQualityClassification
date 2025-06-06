# 🍌 Banana Quality Analysis

## 📊 Project Overview

This project explores the characteristics and quality indicators of various banana varieties. Using a structured dataset, we analyze factors such as ripeness, sugar content, firmness, and environmental conditions to gain insights into banana quality and the conditions influencing it.

## 📁 Dataset Description

The dataset includes the following variables:

| Variable | Description |
|----------|-------------|
| `variety` | Banana variety (e.g., Blue Java, Cavendish, Plantain) |
| `region` | Country/region where the banana was grown |
| `quality_category` | Quality category of the banana (Good, Premium, etc.) |
| `ripeness_index` | Numeric index of ripeness (1.02 - 7.00) |
| `ripeness_category` | Ripeness category (Green, Ripe, etc.) |
| `sugar_content_brix` | Sugar content (Brix scale) |
| `firmness_kgf` | Firmness (kgf - kilogram-force) |
| `length_cm` | Length of the banana in cm |
| `weight_g` | Weight in grams |
| `harvest_date` | Harvest date |
| `tree_age_years` | Age of the banana tree |
| `altitude_m` | Altitude in meters where the tree was grown |
| `rainfall_mm` | Total rainfall in the growing region |
| `soil_nitrogen_ppm` | Soil nitrogen content in ppm |

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn** 
- **Scikit-learn** 

## 📈 Project Goals

- Understand the relationships between banana attributes.
- Categorize banana ripeness and quality.
- Explore environmental influences on banana characteristics.
- Build predictive models for quality or ripeness.

## 📂 Project Structure

- `projekt.ipynb`: Main analysis notebook.
- `README.md`: Project overview and instructions.

## 🚀 Getting Started

To run the project:

```bash
git clone <your-repo-url>
cd <project-directory>
pip install -r requirements.txt
jupyter notebook projekt.ipynb
```

## 📌 Future Work

- Expand dataset to include more regions and years.
- Visualize changes over time (if time series data is available).
