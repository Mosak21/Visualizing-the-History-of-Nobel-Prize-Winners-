# Nobel Prize Data Analysis Project

### Overview

This repository contains an exploratory data analysis (EDA) project using the **Nobel Prize** dataset, spanning from the first award in 1901 to 2023. The Nobel Prize is one of the most prestigious international awards, recognizing achievements in chemistry, literature, physics, physiology or medicine, economics, and peace. In this project, we analyze patterns and insights from over a century of Nobel Prize data.

The dataset is sourced from the Nobel Prize API and can be found in the `nobel.csv` file within the `data` folder.

### Objectives

The project aims to explore the following key questions related to the Nobel Prize data:
1. **Who are the most frequent recipients of the Nobel Prize?**
2. **What are the trends over time in terms of countries, categories, and gender?**
3. **Are there patterns in multiple-time recipients, prize distribution across continents, or the rise of certain fields?**
4. **What are some interesting historical moments, anomalies, or trends in the data?**

Additionally, we encourage further exploration of questions that may spark your curiosity, such as:
- What is the average age of Nobel Prize winners by category?
- Which countries have the highest number of laureates in each discipline?

### Data

The **Nobel Prize** dataset (`nobel.csv`) includes the following key features:
- **Year**: The year the prize was awarded.
- **Category**: The field in which the prize was awarded (e.g., Physics, Chemistry).
- **Laureate**: The name(s) of the Nobel Prize recipients.
- **Country**: The country of the recipient(s).
- **Motivation**: The reason for awarding the prize.
- **Gender**: The gender of the recipients.

### Installation

Clone the repository to your local machine:
```
git clone https://github.com/your-username/nobel-prize-analysis.git
```

### Dependencies

The analysis can be performed using the following Python libraries:
- pandas
- matplotlib
- seaborn
- numpy

You can install them using pip:
```
pip install pandas matplotlib seaborn numpy
```

### Running the Analysis

1. Load the dataset using pandas:
   ```python
   import pandas as pd
   df = pd.read_csv('data/nobel.csv')
   ```

2. Follow the analysis steps in the `nobel_analysis.ipynb` Jupyter notebook to explore trends in Nobel Prize history.

### Results

- **Top Countries**: Which countries lead in producing Nobel laureates.
- **Gender Trends**: An analysis of gender representation over time.
- **Category Insights**: Patterns in awards for different categories (e.g., Physics, Literature).
- **Age Distribution**: Distribution of laureates’ ages across various disciplines.

### Contributing

Contributions are welcome! If you have new questions or insights to explore, feel free to open issues or submit pull requests.

---

