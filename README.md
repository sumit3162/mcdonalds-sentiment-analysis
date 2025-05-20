# McDonald's Customer Sentiment Analysis

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

This project analyzes customer survey data about McDonald's to understand customer sentiment and identify key factors influencing satisfaction.

## 📌 Features

- Comprehensive data cleaning and preprocessing
- Exploratory data analysis with visualizations
- Statistical tests (chi-square, correlation analysis)
- Predictive modeling (linear regression)
- Customer segmentation (K-means clustering)
- 12+ interactive visualizations

## 📊 Key Insights

1. Younger customers (under 30) show more positive sentiment than older groups
2. "Convenient", "fast", and "cheap" are the most valued attributes
3. Frequent visitors are more likely to have positive sentiment
4. Four distinct customer segments identified through clustering

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sumit3162/mcdonalds-sentiment-analysis.git
   cd mcdonalds-sentiment-analysis
   ```

2. Set up a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 📈 Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `McDonalds_Sentiment_Analysis.ipynb`

3. Run all cells to see the complete analysis

## 📂 File Structure

```
mcdonalds-sentiment-analysis/
├── McDonalds_Sentiment_Analysis.ipynb  # Main analysis notebook
├── mcdonalds.csv                       # Dataset
├── requirements.txt                    # Dependencies
├── README.md                           # This file
└── images/                             # Generated visualizations
```

## 📋 Requirements

- Python 3.8+
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install all requirements with:
```bash
pip install -r requirements.txt
```

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📧 Contact

Your Name - your.email@example.com

Project Link: [https://github.com/sumit3162/mcdonalds-sentiment-analysis](https://github.com/sumit3162/mcdonalds-sentiment-analysis)
```

## Additional GitHub Setup Recommendations

1. **Repository Topics**: Add relevant topics like:
   - `data-analysis`
   - `customer-sentiment` 
   - `jupyter-notebook`
   - `data-visualization`
   - `market-research`

2. **.gitignore**: Create a `.gitignore` file for Python/Jupyter:
   ```
   __pycache__/
   *.py[cod]
   *$py.class
   .ipynb_checkpoints
   .DS_Store
   .env
   venv/
   ```

3. **requirements.txt**: Create with:
   ```
   numpy==1.21.5
   pandas==1.3.5
   matplotlib==3.5.1
   seaborn==0.11.2
   scikit-learn==1.0.2
   jupyter==1.0.0
   ```

This setup provides a professional, well-documented GitHub repository that clearly communicates your project's value and makes it easy for others to understand and reproduce your analysis.
