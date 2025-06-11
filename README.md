# Automotive Data Analysis and Visualization 

This Python-based data analysis project focused on cleaning, transforming, and exploring a comprehensive automotive dataset to prepare it for meaningful insights and potential machine learning applications. Through systematic data cleaning, feature engineering, and exploratory analysis, the project uncovered key trends related to vehicle pricing, performance, and fuel efficiency—enhancing the dataset's quality and analytical value.

---

## 📂 Project Overview

This project includes:

- Loading and inspecting raw automotive data
- Cleaning missing values
- Performing data type conversions
- Exploratory Data analysis (EDA)
- Corelation Analysis
- Saving the cleaned dataset for future use

---

## 🧰 Technologies Used

- Python 
- Pandas (Data cleaning and manipulation)
- Matplotlib and Seaborn (Data Visulization)
- Google Colab / Jupyter Notebook (Develpoment area)

---

## 📊 Dataset

The dataset includes various attributes of vehicles such as:
- Make and Model
- Engine specifications (HP, Cylinders, Fuel Type)
- Market category
- Number of doors
- Year of manufacture

---
## 🧭 How to Run This Project in Google Colab

### Step 1: Open Google Colab
- Go to [Google Colab](https://colab.research.google.com/)

---

### Step 2: Clone the GitHub Repository

In a new Colab notebook, run:

```python
!git clone https://github.com/prathikshaghasari/automotive-eda-python.git
```
---

### Step 3: Navigate to the Project Directory

```python
%cd automotive-data-analysis
```

---

### Step 4: Open the Notebook

- Click **File > Open notebook** in the Colab menu.
- Choose the **GitHub** tab and paste your repository URL.
- Select the notebook file (e.g., `automotive_analysis.ipynb`).

---

### Step 5: Load or Upload the Dataset

If the dataset isn't included:
- Use the **left sidebar in Colab** to upload `car_dataset_analysis.csv`
- Or mount your Google Drive with:

```python
from google.colab import drive
drive.mount('/content/drive')
```

---

### Step 6: Run the Analysis

- Execute the notebook cells in order.
- Install any missing libraries if needed:

```python
!pip install seaborn
```

---


## 🔧 Data Cleaning Steps

- Identified and handled missing values using appropriate strategies (mean, median, mode, placeholders).
- Converted data types to ensure consistency and enable proper analysis (e.g., converting `Engine HP` to float).
- Removed duplicates (if any) and standardized categorical values.
- Created visualizations such as histograms, scatter plots, and box plots to illustrate relationships between key variables, including drivetrain type, vehicle size, and transmission type.
- Generated summary statistics to quantify trends in vehicle pricing, performance, and efficiency across various categories, supporting data-driven insights.

## 💡 Outcome

The project successfully transformed raw automotive data into a structured, insight-rich dataset through robust cleaning, transformation, and exploratory analysis. By uncovering key relationships between price, performance, fuel efficiency, and market trends, the project enables data-driven decision-making for both strategic product positioning and targeted marketing. The insights can directly inform business strategies—such as aligning vehicle offerings with consumer affordability preferences, optimizing feature-value trade-offs, and leveraging brand perception to boost sales. The prepared dataset is also well-suited for future machine learning applications, such as price prediction, customer segmentation, or demand forecasting.

---

## 👤 Author

**Prathiksha Prashant Ghasari**  
GitHub: [github.com/prathikshaghasari](https://github.com/prathikshaghasari)

---
