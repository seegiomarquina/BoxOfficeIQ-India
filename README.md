#  BoxOfficeIQ India — Indian Cinema Revenue Intelligence

### Machine Learning | Box Office Analytics | Revenue Prediction

**BoxOfficeIQ India** is a Data Science and Machine Learning project that analyzes Indian cinema's box-office performance across multiple film industries and explores the relationship between production budgets, genres, languages, release timing, and worldwide collections.

The project also features a dedicated scenario-analysis case study inspired by **Namit Malhotra's Ramayana**, using historical Indian cinema data to demonstrate how machine learning can support hypothetical movie revenue analysis.

---

## 🎯 Project Objectives

- Analyze historical Indian movie box-office performance.
- Explore revenue patterns across different Indian film industries.
- Understand the relationship between production budgets and worldwide collections.
- Identify high-performing genres and languages.
- Build machine learning models to estimate worldwide movie collections.
- Compare multiple regression algorithms.
- Perform feature importance analysis.
- Develop a hypothetical Ramayana revenue scenario simulator.

## 📊 Dataset

**Dataset:** Indian Movies Box Office Collection (2014–2024)

**Source:** [Indian Movies Box Office Collection — GitHub](https://github.com/arvindbadagi/Indian-Movies-Box-Office-Collection)

The dataset contains historical Indian movie information, including:

- Movie titles
- Release dates
- Production budgets
- Worldwide collections
- India gross collections
- Film industries
- Languages
- Genres
- Directors
- Lead actors

**Target Variable:** Worldwide Collection (₹ Crores)

The dataset is automatically downloaded and processed within Google Colab.

## 🛠️ Technologies Used

| Technology | Application |
|---|---|
| Python | Core programming |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning |
| Joblib | Model serialization |
| Google Colab | Development environment |

## ⚙️ Project Workflow

**1. Data Acquisition**
- Automatically retrieve the Indian cinema dataset.
- Load and merge supporting dimension tables.

**2. Data Cleaning**
- Handle missing values.
- Remove duplicate records.
- Convert financial values into numerical formats.
- Standardize dates and categorical variables.

**3. Exploratory Data Analysis**
- Movie revenue distribution.
- Budget versus worldwide collection.
- Industry-wise performance.
- Language-wise movie distribution.
- Genre performance.
- Yearly release trends.
- Correlation analysis.

**4. Feature Engineering**
- Production budget.
- Runtime.
- Release year and month.
- Director.
- Lead actor.
- Language.
- Film industry.
- Genre.

**5. Machine Learning**

Three regression algorithms are implemented:

- Ridge Regression
- Random Forest Regressor
- Extra Trees Regressor

**6. Model Evaluation**

Models are compared using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

**7. Ramayana Scenario Analysis**

A hypothetical scenario simulator allows users to provide assumptions such as production budget, runtime, release timing, language, industry, and genre.

The trained model generates an experimental worldwide revenue estimate and budget sensitivity analysis.

## 📈 Key Visualizations

The project generates visualizations covering:

- Top 10 Indian movies by worldwide collection.
- Production budget versus worldwide collection.
- Industry-wise performance.
- Language distribution.
- Genre-wise revenue analysis.
- Yearly movie releases.
- Financial correlation heatmap.
- Model comparison.
- Actual versus predicted revenue.
- Feature importance.
- Ramayana budget sensitivity analysis.

## 🏗️ Project Structure

```text
BoxOfficeIQ_India/
│
├── README.md
├── requirements.txt
│
├── data/
│   └── cleaned_indian_movies.csv
│
├── models/
│   └── boxoffice_model.joblib
│
├── outputs/
│   ├── top_10_movies.png
│   ├── budget_vs_worldwide.png
│   ├── industry_comparison.png
│   ├── language_distribution.png
│   ├── genre_performance.png
│   ├── yearly_releases.png
│   ├── correlation_heatmap.png
│   ├── model_comparison.png
│   ├── actual_vs_predicted.png
│   ├── feature_importance.png
│   └── ramayana_sensitivity.png
│
└── reports/
    ├── model_evaluation.csv
    ├── feature_importance.csv
    ├── ramayana_scenario.csv
    ├── ramayana_sensitivity.csv
    └── source_information.json
```

## 🚀 How to Run

1. Clone or download this repository.
2. Open the Google Colab notebook.
3. Execute the complete notebook.
4. The dataset downloads automatically.
5. Explore the analysis, model evaluation, and scenario simulator.

**Development Environment:** Google Colab

## 🔍 Important Limitations

- The dataset is community-maintained and is not an audited official box-office database.
- Historical movie records may contain incomplete or inconsistent financial information.
- The number of records is limited compared with the full Indian film industry.
- The model may not generalize to films outside its historical training distribution.
- Worldwide gross collection is not equivalent to producer profit.
- The Ramayana scenario is an experimental model-generated estimate, not verified box-office information or an investment forecast.

## 🔮 Future Improvements

- Integrate a larger and independently verified Indian box-office dataset.
- Incorporate marketing expenditure and theatrical screen counts.
- Analyze audience sentiment using NLP.
- Add regional and international market-level analysis.
- Develop an interactive Streamlit dashboard.
- Experiment with advanced gradient boosting algorithms.
- Improve model validation using larger chronological datasets.

## 👨‍💻 Project Information

**Project:** BoxOfficeIQ India

**Category:** Data Science | Machine Learning | Business Analytics

**Environment:** Google Colab

**Focus:** Indian Cinema and Box Office Revenue Intelligence

---

*An independent Data Science portfolio project exploring how historical cinema data can be transformed into meaningful business insights using machine learning.*
