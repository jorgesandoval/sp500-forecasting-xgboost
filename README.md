# S&P 500 Index Forecasting using XGBoost

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![GitHub Stars](https://img.shields.io/github/stars/jorgesandoval/sp500-forecasting-xgboost.svg)
![GitHub Downloads](https://img.shields.io/github/downloads/jorgesandoval/sp500-forecasting-xgboost/total.svg)
![GitHub Forks](https://img.shields.io/github/forks/jorgesandoval/sp500-forecasting-xgboost.svg)


![Alt text](images/SP500Forecasting.png)
This repository houses a Jupyter notebook showcasing the XGBoost for forecasting the S&P 500 index using time-series data.



## 📖 Table of Contents
- [S\&P 500 Index Forecasting using XGBoost](#sp-500-index-forecasting-using-xgboost)
  - [📖 Table of Contents](#-table-of-contents)
  - [📌 Overview](#-overview)
  - [📊 Dataset](#-dataset)
  - [🔧 Dependencies](#-dependencies)
  - [🚀 Usage](#-usage)
  - [📈 Key Findings](#-key-findings)
  - [💡 Contributions](#-contributions)
  - [📜 License](#-license)
  - [👤 Authors](#-authors)
  - [🙌 Acknowledgements](#-acknowledgements)

## 📌 Overview
The notebook ingests historical S&P 500 Index data, preprocesses it, and then employs the XGBoost regression model to forecast the index. The model's performance is evaluated using metrics such as Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (Coefficient of Determination).

## 📊 Dataset

* **File Name**: `sp500_index.csv`
* **Description**: The dataset contains historical values of the S&P 500 Index. The data is cleaned by handling null values and removing rows with zero values in the 'S&P500' column. The dataset is then visualized to provide a clear view of the S&P 500 Index over time.

## 🔧 Dependencies

To run the notebook, you'll need the following libraries:

- pandas
- numpy
- matplotlib
- scikit-learn
- xgboost

You can install these using `pip`:

```bash
pip install pandas numpy matplotlib scikit-learn xgboost
```

## 🚀 Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/sp500-forecasting-xgboost.git
   ```
2. **Navigate to the cloned directory and open the Jupyter notebook"**

    ```bash
    cd sp500-forecasting-xgboost
    jupyter notebook
    ```
3. **Run the notebook**: Execute the notebook cells sequentially to preprocess the data, train the XGBoost model, and evaluate its performance.
## 📈 Key Findings

* Consistent rise from 2014 to mid-2017.
* Fluctuations and a notable decline around 2018.
* Surge from early 2019 to 2020.
* Sharp decline in 2020, likely indicating an economic downturn.
* Swift recovery leading into 2022.
* Relative stability with minor oscillations from 2022 to 2024.
* Root Mean Squared Error (RMSE): 52.67, indicating an average deviation of approximately 52.67 points from the actual S&P 500 index values.
* Mean Absolute Error (MAE): 21.41, signifying an average absolute error of 21.41 points in the model's predictions.
* R-squared value: 0.97 (or 91%), suggesting that the model explains 91% of the variance in the S&P 500 index.
* Actual vs. Predicted Analysis: The XGBoost model's predictions generally followed the actual trajectory of the S&P 500 Index.
* While the overall trend was captured, there were specific instances where the model's predictions deviated from the actual values.

## 💡 Contributions

Contributions to this repository are very welcome! Whether it's fixing bugs, improving the documentation, adding new features, or providing feedback, your insights can help improve this project. Here's how you can contribute:

1. **Fork the Project**
* Navigate to the main page of the repository.
* Click on the Fork button on the top right.

2. **Create Your Feature Branch**
    ```bash
    git checkout -b feature/AmazingFeature
    ```

3. **Commit Your Changes**
    ```bash
    git commit -m 'Add some AmazingFeature'
    ```
4. **Push to the Branch**
    ```bash
    git push origin feature/AmazingFeature
    ```
5. **Open a Pull Request**
* Navigate back to the main page of your forked repository.
* Click on the "Pull requests" tab.
* Click on the green "New pull request" button.


## 📜 License

Distributed under the MIT License. See [LICENSE](https://opensource.org/licenses/MIT) for more information.

## 👤 Authors
* [Jorge Sandoval](https://www.linkedin.com/in/jorge-g-sandoval/)

## 🙌 Acknowledgements

I would like to acknowledge and express my gratitude to the Standard and Poor's 500 (S&P 500) for being a cornerstone in the world of finance. Recognized globally as the premier financial benchmark, the S&P 500 diligently tracks the performance of 500 eminent companies listed on U.S. stock exchanges. It's noteworthy to mention that as of December 31, 2020, the index had influenced investments exceeding $5.4 trillion in assets, a testament to its significance in the financial landscape.

A special mention to the intricacies of the index: while it's named the S&P 500, it encompasses 505 stocks, factoring in multiple classes of stock from certain constituent companies, such as Alphabet's Class A (GOOGL) and Class C (GOOG).

I deeply appreciate the transparency, consistency, and dedication with which the S&P 500 operates, providing invaluable insights and benchmarks for investors and financial analysts worldwide.


