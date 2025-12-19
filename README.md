# 💳 Credit Card Approval Predictor

This is a machine learning project from **Datacamp** that predicts credit card application approvals using scikit-learn.  This project demonstrates data preprocessing, exploratory data analysis, and building a classification model to determine whether a credit card application should be approved or rejected.

![Credit Card](credit_card.jpg)

## 📋 Project Overview

Commercial banks receive thousands of credit card applications daily, many of which get rejected for various reasons such as high loan balances, low income levels, or too many credit inquiries.  Manually analyzing these applications is time-consuming and error-prone.  This project automates the credit card approval process using machine learning techniques.

## 🎯 Objectives

- **Data Preprocessing**: Handle missing values and prepare data for machine learning
- **Exploratory Data Analysis**: Understand patterns and relationships in credit card applications
- **Feature Engineering**:  Transform and scale features for optimal model performance
- **Model Building**: Train a classification model to predict approval/rejection
- **Model Evaluation**: Assess model performance using appropriate metrics

## 📁 Repository Structure

```
Scikit-CredCard-Predictor/
│
├── notebook.ipynb          # Main Jupyter notebook with complete analysis
├── cc_approvals.data       # Dataset containing credit card applications
├── credit_card.jpg         # Project thumbnail image
└── LICENSE                 # MIT License
```

## 🛠️ Technologies Used

- **Python 3.x**
- **scikit-learn** - Machine learning library
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib/seaborn** - Data visualization

## 🚀 Getting Started

### Prerequisites

```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Ratul-byte/Scikit-CredCard-Predictor.git
cd Scikit-CredCard-Predictor
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook notebook.ipynb
```

## 📊 Dataset

The project uses the `cc_approvals.data` file, which contains various features of credit card applicants such as:
- Income level
- Credit history
- Employment status
- Age and other demographic information
- Previous loan balances
- And more...

## 🔍 Methodology

1. **Data Loading**: Import and inspect the credit card applications dataset
2. **Data Cleaning**: Handle missing values and outliers
3. **Feature Selection**: Identify relevant features for prediction
4. **Data Preprocessing**: Encode categorical variables and scale numerical features
5. **Model Training**: Build and train classification models
6. **Model Evaluation**: Assess performance using accuracy, precision, recall, and F1-score
7. **Prediction**: Make predictions on new credit card applications

## 📈 Results

The notebook contains detailed analysis and results of the credit card approval prediction model, including:
- Model accuracy and performance metrics
- Feature importance analysis
- Confusion matrix and classification reports

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. You can find the original Datacamp Project Page here in this [link](https://app.datacamp.com/learn/projects/1908)

## 👤 Author

**Ratul-byte**
- GitHub: [@Ratul-byte](https://github.com/Ratul-byte)

## 🌟 Acknowledgments

- Dataset source: Credit card applications dataset
- Inspired by real-world banking automation challenges
- Built with scikit-learn and data science best practices

---

⭐ If you found this project helpful, please consider giving it a star! 
```
