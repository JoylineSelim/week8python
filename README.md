# COVID-19 Global Data Tracker

![COVID-19 Dashboard Example](https://ourworldindata.org/uploads/2020/03/COVID-19-positive-rate-vs-testing-rate-768x576.png)

## Project Description
This project analyzes global COVID-19 trends including cases, deaths, recoveries, and vaccination progress across different countries. The analysis is presented in a Jupyter Notebook with interactive visualizations and data-driven insights about the pandemic's progression.

## Objectives
- Import and clean real-world COVID-19 data from reliable sources
- Analyze time trends in cases, deaths, and vaccinations
- Compare metrics across different countries/regions
- Visualize trends with multiple chart types (line, bar, choropleth maps)
- Generate actionable insights from the data analysis

## Tools and Libraries Used
- **Python 3**
- **Jupyter Notebook**
- **Data Processing**:
  - pandas
  - numpy
- **Visualization**:
  - matplotlib
  - seaborn
  - plotly.express
- **Additional Utilities**:
  - datetime
  - warnings

## Dataset
The analysis uses the [Our World in Data COVID-19 Dataset](https://ourworldindata.org/covid-cases), which includes:
- Daily updated COVID-19 statistics
- Vaccination data
- Testing information
- Demographic context

## How to Run the Project

### Prerequisites
1. Install Python 3.x
2. Install Jupyter Notebook:

   pip install notebook

3. Install required packages:
pip install pandas numpy matplotlib seaborn plotly


### Running the Notebook
1. Download the dataset:
wget https://covid.ourworldindata.org/data/owid-covid-data.csv

2. Clone this repository:
git clone [repository-url]

3. Launch Jupyter Notebook:
jupyter notebook

4. Open `COVID-19_Global_Data_Tracker.ipynb`
5. Run all cells (Kernel > Restart & Run All)

### Alternative Viewing
For quick viewing without running the notebook:
1. View the static notebook on GitHub
2. View the rendered notebook on [nbviewer](https://nbviewer.org/)

## Key Insights
1. **Case Trends**:
- The United States consistently showed the highest total cases among analyzed countries
- All countries exhibited wave-like patterns of infection

2. **Vaccination Progress**:
- Developed nations achieved significantly higher vaccination rates
- Vaccination timelines correlated with subsequent case reductions

3. **Regional Differences**:
- Europe and Americas showed highest cases per capita
- Africa reported lower cases but with likely under-testing

4. **Death Rates**:
- Mortality rates improved over time, suggesting better treatments
- Brazil showed unusually high death rates compared to similar countries

## Reflections
This project demonstrated:
- The power of Python for processing large-scale pandemic data
- How visualization can reveal patterns not obvious in raw numbers
- The global disparity in pandemic response and outcomes
- Challenges with missing/incomplete data in real-world datasets

Future enhancements could include:
- Interactive dashboard using Dash or Streamlit
- Machine learning predictions
- Integration with additional data sources (economic, mobility)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
