 Task 1: Exploring and Visualizing the Iri

🎯 Objective

The objective of this task is to load, inspect, explore, and visualize the Iris dataset in order to understand its structure, feature distributions, and relationships between variables. This task demonstrates basic data exploration and visualization skills using Python.

📊 Dataset Used

Iris Dataset

Source: seaborn built-in dataset

Total Samples: 150

Total Columns: 5

Features:

sepal_length

sepal_width

petal_length

petal_width

Target:

species

🛠️ Libraries Used

pandas – for data loading and exploration

matplotlib – for plotting and saving visualizations

seaborn – for dataset loading and advanced visualizations

🔍 Steps Performed
1️⃣ Import Libraries

All required Python libraries are imported for data handling and visualization.

2️⃣ Load Dataset

The Iris dataset is loaded directly from Seaborn using:

sns.load_dataset('iris')

3️⃣ Explore Dataset

The following exploratory steps are performed:

Dataset shape (rows × columns)

Column names

First 5 rows preview

Data types and missing values

Descriptive statistics (mean, min, max, etc.)

📈 Visualizations Created
🔹 Scatter Plot

Sepal Length vs Sepal Width

Colored by species to observe class separation

Saved as: scatter_plot.png

🔹 Histograms

Distribution of all numerical features

Helps understand spread and frequency

Saved as: feature_histograms.png

🔹 Box Plot

Detects potential outliers across features

Saved as: box_plot.png

📌 Key Insights

The dataset contains 150 samples and no missing values

Species show clear separation based on feature dimensions

Feature distributions are mostly well-balanced

Box plots help identify possible outliers

The Iris dataset is ideal for learning data exploration and visualization


✅ Conclusion

This task successfully demonstrates basic exploratory data analysis (EDA) using Python. It covers dataset inspection, statistical analysis, and multiple visualization techniques, making it a strong foundation for further machine learning tasks.

