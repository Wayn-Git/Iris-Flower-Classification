# Iris Flower Classifier 🌸

A machine learning project that classifies iris flowers into three species (Setosa, Versicolor, and Virginica) using a Random Forest classifier. This project demonstrates the complete machine learning pipeline from data exploration to model evaluation.

## 📊 Dataset

The project uses the famous Iris dataset, which contains:
- **150 samples** of iris flowers
- **4 features**: sepal length, sepal width, petal length, petal width
- **3 species**: Setosa, Versicolor, Virginica
- **50 samples** per species

## 🚀 Features

- **Data Exploration**: Comprehensive analysis including shape, info, and statistical summary
- **Data Visualization**: Pairplot visualization to understand feature relationships
- **Data Quality Checks**: Missing values and duplicate detection
- **Data Preprocessing**: Feature scaling using StandardScaler
- **Machine Learning**: Random Forest classification
- **Model Evaluation**: Accuracy scoring and performance metrics

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization
- **scikit-learn** - Machine learning library

## 📋 Prerequisites

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/iris-flower-classifier.git
cd iris-flower-classifier
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Ensure you have the `iris.csv` file in your project directory

## 💻 Usage

Run the main script:
```bash
python iris_classifier.py
```

The script will:
1. Load and explore the iris dataset
2. Visualize feature relationships
3. Check for data quality issues
4. Preprocess the data
5. Train a Random Forest model
6. Evaluate model performance

## 📈 Model Performance

The Random Forest classifier achieves high accuracy on the iris dataset due to the dataset's well-separated classes and distinct feature patterns.

## 🔍 Code Structure

```
iris-flower-classifier/
│
├── iris_classifier.py      # Main classification script
├── iris.csv               # Dataset file
├── requirements.txt       # Python dependencies
└── README.md             # Project documentation
```

## 📊 Data Analysis Highlights

- **No missing values** detected in the dataset
- **Balanced dataset** with equal representation of all species
- **Clear feature separation** visible in pairplot visualizations
- **Well-distributed features** across different species

## 🎯 Machine Learning Pipeline

1. **Data Loading**: Load iris dataset from CSV
2. **Exploratory Data Analysis**: 
   - Dataset shape and structure analysis
   - Statistical summary
   - Species distribution
   - Feature relationship visualization
3. **Data Quality Assessment**:
   - Missing value detection
   - Duplicate checking
4. **Data Preprocessing**:
   - Feature scaling using StandardScaler
   - Train-test split (80-20)
5. **Model Training**:
   - Random Forest Classifier
   - Model fitting on scaled training data
6. **Model Evaluation**:
   - Predictions on test set
   - Accuracy calculation

## 🔧 Code Issues & Improvements

**Note**: The provided code has some issues that should be addressed:

1. **Import Error**: Missing `StandardScaler` import
2. **Undefined Variable**: `iris` object is used without definition
3. **Redundant Operations**: Multiple unnecessary dataframe operations
4. **Code Organization**: Can be streamlined for better readability


## 🚀 Future Enhancements

- [ ] Add cross-validation for more robust evaluation
- [ ] Implement multiple algorithms comparison
- [ ] Add confusion matrix and classification report
- [ ] Create interactive visualizations
- [ ] Add model persistence (save/load)
- [ ] Implement hyperparameter tuning
- [ ] Add ROC curves and precision-recall metrics

## 📝 Requirements

Create a `requirements.txt` file with:
```
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=1.0.0
numpy>=1.21.0
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
com/yourusername)

## 🙏 Acknowledgments

- UCI Machine Learning Repository for the Iris dataset
- Scikit-learn community for excellent documentation
- Python data science community

---

**Note**: This is an educational project demonstrating basic machine learning concepts with the classic Iris dataset.
