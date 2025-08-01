
# 🧠 NeuroCure-ML

A machine learning-powered application designed to predict diseases based on user-input symptoms. This project uses classification models trained on real-world medical symptom-disease datasets.

---

## 🚀 Features

- User symptom input
- Predictive model outputs possible diseases
- Trained on medical datasets
- Clean CLI-based user interaction
- Modular Python codebase

---

## 🛠️ Tech Stack

| Category        | Technology Used            |
|----------------|-----------------------------|
| Programming    | Python 3.10+                |
| ML Libraries   | Scikit-learn, Pandas, NumPy |
| Visualization  | Matplotlib                  |
| Flowchart Tool | draw.io / mermaid.js        |
| Environment    | Jupyter Notebook            |
| Version Control| Git + GitHub                |

---

## 📈 Flowchart

```mermaid
flowchart TD
    A[Start] --> B[User inputs symptoms]
    B --> C[Preprocess inputs]
    C --> D[Load trained ML model]
    D --> E[Model predicts disease]
    E --> F[Display predicted disease to user]
    F --> G[End]
````


## ⚙️ Installation

```bash
git clone https://github.com/AdeshAJ/NeuroCure-ML.git
cd NeuroCure-ML
pip install -r requirements.txt
```

---

## 🧪 Usage

```bash
python main.py
```

Or run via Jupyter Notebook:

```bash
jupyter notebook
```

Enter symptoms as prompted. The model will predict the most probable disease.

---

## 📂 Project Structure

```
NeuroCure-ML/
├── main.py
├── model/
│   ├── train_model.py
│   └── disease_predictor.pkl
├── data/
│   └── symptom_disease_dataset.csv
├── notebooks/
│   └── EDA_and_Modeling.ipynb
├── requirements.txt
└── README.md
```

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

* Dataset from open-source medical datasets
* Inspiration from real-life symptom checkers

````

