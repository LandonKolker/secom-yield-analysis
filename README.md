# SECOM Yield Analysis

This project explores and analyzes the SECOM dataset from the UCI Machine Learning Repository. It focuses on semiconductor manufacturing yield data, with the goal of uncovering patterns, cleaning the data, visualizing relationships, and building predictive models to classify product quality.

## 📁 Project Structure
secom-yield-analysis/
├── data/ # Raw and processed data files
├── notebooks/ # Jupyter notebooks for analysis
├── .gitignore
├── README.md # Project overview and instructions
└── requirements.txt # Python dependencies

## 📊 Dataset

- Source: [UCI Machine Learning Repository – SECOM](https://archive.ics.uci.edu/ml/datasets/secom)
- `secom.data`: Sensor measurements from manufacturing
- `secom_labels.data`: Pass/fail labels and timestamps

## 🧪 Goals

- Clean and explore the dataset
- Visualize key features and trends
- Handle missing values and outliers
- Train ML models (e.g., logistic regression, random forest)
- Evaluate performance on predicting failures

## ⚙️ Setup

1. Clone the repo:
   git clone https://github.com/lkokr2424/secom-yield-analysis.git
   cd secom-yield-analysis

2. (Optional) Create a virtual enviornment:
    python -m venv venv
    source venv/bin/activate  # or venv\Scripts\activate on Windows

3. Install dependancies:
    pip install -r Requirements.txt


## 🧠 Author

- Landon Kolker  
- Bachelor's in Industrial Engineering  
- Exploring data science and machine learning using Python after a 3-year career gap
- LinkedIn : [linkedin.com/in/landon-kolker](https://www.linkedin.com/in/landon-kolker-b246601a0/)

## 📌 Future Work

- Perform in-depth feature selection and dimensionality reduction
- Explore time-based patterns in the manufacturing process
- Improve model performance with hyperparameter tuning
- Build a dashboard or app to present results interactively (e.g., with Streamlit)

## 🪪 License

This project is open source and available under the [MIT License](LICENSE).  
The dataset is provided by the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/secom) for academic use.

---

_This project is a portfolio piece to demonstrate my data analysis and machine learning skills. Feedback and collaboration are welcome!_
