# Ticket-Prediction
```markdown
# 🚆 Train Ticket Confirmation Predictor

A machine learning project to predict the confirmation status of Indian train tickets based on booking and journey details.

## 📂 Repository Structure

```
├── Ticket_prediction.ipynb      # Jupyter Notebook with end-to-end model workflow
├── train_data.csv               # Raw dataset used for training
├── train_ticket_model.pkl       # Serialized Random Forest model
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
```

## 🎯 Objectives

- **Data Preprocessing**: Handle missing values, compute booking lead time.
- **Feature Engineering**: Encode categorical variables and scale numeric ones.
- **Model Training**: Random Forest classifier with hyperparameters suited for tabular data.
- **Evaluation**: Accuracy score and classification report.
- **Interactive Prediction**: Jupyter-driven prompts or CLI-style inputs for new examples.

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- `pip` package manager

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/<your-username>/train-ticket-predictor.git
    cd train-ticket-predictor
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## 📒 Usage

### 1. Jupyter Notebook

1. Launch Jupyter:
    ```bash
    jupyter notebook Ticket_prediction.ipynb
    ```
2. Run all cells sequentially.
3. Follow the interactive prompts to enter booking details and get prediction results.

### 2. Python Script (CLI)

*(Optional: convert notebook to script or use provided script)*

```bash
python ticket_predictor.py       # if you convert the notebook to .py
```

- The script will ask for booking date, travel date, and other features.
- Outputs prediction (`Confirmed` / `Not Confirmed`) and confidence.

## 🛠️ Features

- **Booking Lead Time**: Days between booking and travel.
- **Train Details**: Train type, number, source & destination stations.
- **Passenger Info**: Age, gender, special considerations (Senior Citizen / PH).
- **Waitlist & Availability**: Positions and seat counts.

## 📊 Model Performance

- **Accuracy**: ~`0.XX`
- **Classification Report**: Precision, recall, and F1-score for both classes.

*(See `Ticket_prediction.ipynb` for full evaluation.)*

## 🤝 Contributing

Contributions are welcome! Please open issues or pull requests to:
- Improve preprocessing
- Tune model hyperparameters
- Extend feature set
- Add Docker support or CI workflows

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---
© 2025 Your Name. Developed with ♥ for predictive analytics.

