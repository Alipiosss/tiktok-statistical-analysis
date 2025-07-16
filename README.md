# 📊 TikTok Statistical Analysis

This project was developed as part of the **Google Advanced Data Analytics Certificate (Course 4 – The Power of Statistics)**.

## 🎯 Objective

To investigate whether there is a statistically significant difference in the average number of video views between verified and unverified TikTok accounts.

## 🧪 Methodology

- Conducted **Exploratory Data Analysis (EDA)**  
- Computed **descriptive statistics**  
- Performed a **two-sample t-test** (Welch's t-test)  
- Chose a significance level of **0.05**  
- Interpreted the **p-value** and **t-statistic**  

## 📈 Key Findings

- **Unverified accounts had significantly higher average views** than verified accounts.
- The **p-value < 0.0001**, which allowed us to **reject the null hypothesis**.
- This suggests that verification status may not directly correlate with higher visibility.
- Additional variables (such as content type, frequency, or algorithmic influence) may better explain performance.

## 💡 Next Steps

- Develop a **logistic regression model** to explore patterns in engagement and claim status.
- Investigate other predictors such as author ban status, video duration, or content characteristics.

## 🛠️ Tools Used

- Python  
  - `pandas` for data manipulation  
  - `scipy.stats` for hypothesis testing  
  - `seaborn` and `matplotlib` for visualization  

## 📁 Files

- `tiktok_hypothesis_test.ipynb`: Complete analysis notebook  
- `tiktok_dataset.csv`: TikTok video dataset used for the hypothesis test  
- `Activity-TikTok-Course-4-executive-summary SA.pdf`: Executive summary with findings  
- `README.md`: Project summary and documentation

## 📂 How to Run

To run this notebook locally:

1. Clone or download the repository.
2. Make sure you have Python and Jupyter Notebook installed.
3. Place the file `tiktok_dataset.csv` in the same folder as the notebook.
4. Open the notebook and run all cells.

> Note: This notebook is prepared to be run in a **Jupyter Notebook** environment.  
> If you're using Google Colab or another platform, you may need to manually upload the dataset.

## ⚠️ Disclaimer

This project was developed as part of the Google Advanced Data Analytics Certificate on Coursera.

The dataset and general structure (including the hypothesis test scenario and guiding questions) were provided by Coursera for educational purposes.

All Python code, data exploration, statistical analysis, visualizations, and interpretations in this repository were independently developed by the author based on the exercise instructions.

To respect Coursera’s content policy, no proprietary course materials (e.g., full instructions or internal content) are included.

## 📄 License

This project is released under the **CC0 1.0 Universal License**.

## 📬 Contact

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/suzanaalipio)  
or reach out via email at [suzanaalipio@gmail.com](mailto:suzanaalipio@gmail.com)

## 🙋 Author

**Suzana Alípio**
