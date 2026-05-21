# Glass Classification

This project applies machine learning to classify types of glass based on their chemical composition, using the [UCI Glass Identification Dataset](https://www.kaggle.com/datasets/uciml/glass).

## 📊 Dataset

The dataset (`glass.csv`) contains **214 samples** with 9 chemical features and a target class label.

| Feature | Description |
|---------|-------------|
| RI | Refractive Index |
| Na | Sodium |
| Mg | Magnesium |
| Al | Aluminum |
| Si | Silicon |
| K | Potassium |
| Ca | Calcium |
| Ba | Barium |
| Fe | Iron |
| Type | Glass type (1–7, target) |

### Glass Types
- **1** — Building Windows (float processed)
- **2** — Building Windows (non-float processed)
- **3** — Vehicle Windows (float processed)
- **5** — Containers
- **6** — Tableware
- **7** — Headlamps

## 🧪 Notebook

The Jupyter notebook `glass_classificatio-1.ipynb` covers:
- Data loading and exploration
- Exploratory Data Analysis (EDA)
- Feature engineering and preprocessing
- Model training and evaluation

## 🛠️ Requirements

```bash
pip install pandas numpy scikit-learn matplotlib seaborn kagglehub
```

## 🚀 Getting Started

```python
import pandas as pd
data = pd.read_csv('glass.csv')
data.head()
```

## 📁 Repository Structure

```
glass-classification/
├── README.md
├── glass.csv              # Dataset
└── glass_classificatio-1.ipynb   # ML notebook
```

## 👤 Author

**Yusif Imamverdiyev** — [GitHub](https://github.com/artfix3r)
