🌊 Machine Learning-based Groundwater Imputation & Visualization

This repository provides a KNN-based imputation framework for filling missing values in groundwater time series and producing high-quality visualizations for each station across monthly and full-series scales.

🚀 Contents

📊 Data: Groundwater station records (Excel, monthly, 2000–2024+)

🧮 Imputation Method:

KNN (k-nearest neighbors) with temporal proximity

Neighbors: ±2 months, ±5 years of the same month

🤖 Workflow:

Create custom feature matrix

Apply KNN imputation

Reconstruct imputed dataset

Generate Excel outputs & plots

📈 Outputs:

GroundwaterDataImputed.xlsx

Full series plots (Plots of Imputed Series/)

Monthly plots (Monthly Plots of Stations/)

🎨 Visualization: Observed vs. Imputed values highlighted in blue vs. red

🛠️ Methods

Data Preprocessing: Missing values identified and flagged

KNN Imputer: scikit-learn implementation with configurable n_neighbors

Temporal Features: Captures seasonal cycles and multi-year periodicity

Reconstruction: Ensures only NaN values are replaced

📊 Example Plots

✅ Full Time Series per Station

✅ 12 Monthly Subplots per Station (January … December)

✅ High-resolution PNG (600 dpi)

⚡ Highlights

🌍 Focus on groundwater sustainability under data scarcity

🔎 Transparent imputation logic (temporal neighbors only)

📊 Excel-ready outputs for further hydrological or climate modeling

🎨 Publication-quality graphics included automatically
