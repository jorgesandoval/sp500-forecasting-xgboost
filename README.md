# Advanced Feature Engineering for S&P 500 Forecasting Using Permutation Entropy and XGBoost

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![GitHub Stars](https://img.shields.io/github/stars/jorgesandoval/sp500-forecasting-xgboost.svg)
![GitHub Downloads](https://img.shields.io/github/downloads/jorgesandoval/sp500-forecasting-xgboost/total.svg)
![GitHub Forks](https://img.shields.io/github/forks/jorgesandoval/sp500-forecasting-xgboost.svg)

![Alt text](images/PEForecasting.png)
This repository houses a Jupyter notebook showcasing the integration of Permutation Entropy and XGBoost for forecasting the S&P 500 index using time-series data.



## 📖 Table of Contents
- [Advanced Feature Engineering for S\&P 500 Forecasting Using Permutation Entropy and XGBoost](#advanced-feature-engineering-for-sp-500-forecasting-using-permutation-entropy-and-xgboost)
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
The notebook ingests historical S&P 500 Index data, preprocesses it, and then employs the XGBoost regression model combined with Permutation Entropy to forecast the index. The model's performance is evaluated using metrics such as Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (Coefficient of Determination).

## 📊 Dataset

* **File Name**: `sp500_index.csv`
* **Description**: The dataset contains historical values of the S&P 500 Index. The data is cleaned by handling null values and removing rows with zero values in the 'S&P500' column. The dataset is then visualized to provide a clear view of the S&P 500 Index over time.

## 🔧 Dependencies

To run the notebook, you'll need the following libraries:

- pandas
- numpy
- matplotlib
- pyentrp
- scikit-learn
- xgboost

You can install these using `pip`:

```bash
pip install pandas numpy matplotlib pyentrp scikit-learn xgboost
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
3. **Run the notebook**: Execute the notebook cells sequentially to preprocess the data, compute Permutation Entropy features, train the XGBoost model, and evaluate its performance.
## 📈 Key Findings
* The notebook leverages Permutation Entropy to assess the complexity and unpredictability of the time series data.
* Lagged values of the S&P 500 Index are added as features to capture temporal dependencies.
* The XGBoost regressor model is trained and evaluated, with performance metrics displayed at the end of the notebook.

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


