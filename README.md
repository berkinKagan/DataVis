
# Heart Attack Risk Assessment at Zheen Hospital

## Project Overview
This project aims to assess the risk of heart attacks among patients at Zheen Hospital in Erbil, Iraq. Using demographic information, physiological measurements, and biochemical parameters, we develop a machine learning model to understand and evaluate the factors contributing to heart attack risk.

## Dataset Description
The dataset includes the following key features from patients at Zheen Hospital:
- **Age**: Patient's age in years.
- **Gender**: Patient's gender (Male/Female).
- **Heart Rate**: Beats per minute.
- **Blood Pressure**: Systolic and Diastolic measurements (mmHg).
- **Blood Sugar**: Blood glucose levels (mg/dL).
- **CK-MB**: Creatine Kinase-MB activity in the blood.
- **Troponin**: Concentration of Troponin in the blood.

## Requirements
To run the analysis and model training scripts, you will need Python 3.x and the following libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## File Structure
- `data/`: Directory for dataset storage.
- `src/`: Python scripts for data processing and modeling.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and results visualization.
- `models/`: Trained model files.
- `README.md`: This file.

## Setup and Running
1. **Clone the repository:**
   ```bash
   git clone [repository-url]
   cd [repository-name]
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebooks:**
   ```bash
   jupyter notebook
   ```
   Navigate to `notebooks/` and open the desired notebook.

4. **To run scripts:**
   ```bash
   python src/train_model.py
   ```

## Model Information
- **Model Type**: Logistic Regression/Random Forest (as applicable).
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, ROC-AUC.

## Contributors
- [Name 1]
- [Name 2]
- [More Names]

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
- **Lead Researcher**: [Name] - Email: [email]
- **Project Link**: [repository-url]
