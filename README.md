# EDM Sentiment Analysis Project

This project analyzes sentiment from an EDM dataset using Vader sentiment analysis and visualizes the results.

## Project Structure

```
EDM_Sentiment_Analysis_Project/
│
├── notebooks/
│   └── Final_Copy_of_EDM.ipynb   # Jupyter notebook with full analysis
│
├── README.md                     # Project overview and instructions
└── requirements.txt              # Required Python packages
```

## Setup Instructions

1. **Clone or download this repository**.

2. **Create a virtual environment (optional but recommended)**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook notebooks/Final_Copy_of_EDM.ipynb
   ```

## Output

- Generates sentiment plots (e.g., scatter plot of Vader sentiment scores).
- Saves plots to PDF in the current directory.

