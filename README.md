# Gapminder Life Expectancy & GDP Analysis

This project explores global development patterns using the Gapminder dataset, analyzing the relationship between **GDP per capita** and **life expectancy** from 1952–2007. The analysis includes statistical modeling, clustering, and interactive visualizations to understand global development trends.

## 🚀 Features

- **Data Analysis**: Comprehensive exploration of Gapminder dataset
- **Statistical Modeling**: OLS regression analysis by continent and selected countries
- **Machine Learning**: K-Means clustering to identify development patterns
- **Interactive Visualizations**: Animated charts and interactive plots using Plotly
- **Predictive Modeling**: Future predictions (2012, 2017) with confidence intervals
- **Data Cleaning**: Robust preprocessing and outlier handling

## 📂 Repository Structure

```
gapminder-lifeexp-analysis/
├── notebooks/
│   └── CameronBell_GapMinder_Analysis.ipynb  # Main analysis notebook
├── data/
│   └── gapminderDataFiveYear.csv             # Gapminder dataset
├── requirements.txt                           # Python dependencies
└── README.md                                 # This file
```

## 🛠️ Setup & Installation

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   cd gapminder-lifeexp-analysis
   ```

2. **Create and activate virtual environment**:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

## 📊 Analysis Components

### Data Exploration

- Dataset overview and basic statistics
- Missing value analysis
- Data quality assessment

### Statistical Analysis

- Correlation analysis between GDP and life expectancy
- Regression modeling by continent
- Confidence interval calculations

### Machine Learning

- K-Means clustering for development pattern identification
- Silhouette analysis for optimal cluster selection

### Visualizations

- Interactive scatter plots with Plotly
- Animated population bar charts
- Regression line visualizations
- Cluster analysis plots

## 🔧 Tech Stack

- **Data Processing**: Python, Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Machine Learning**: scikit-learn
- **Statistical Analysis**: statsmodels
- **Development**: Jupyter Notebook

## 📈 Key Findings

The analysis reveals:

- Strong positive correlation between GDP per capita and life expectancy
- Distinct development patterns across continents
- Clustering identifies different stages of development
- Predictive models show continued global development trends

## 👤 Author

**Cameron Bell** – MSc Computer Science & Business Technology

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
