# Water Potability Prediction with DVC

This project demonstrates the use of Machine Learning pipelines and version control techniques to predict water potability. The pipeline is managed using **DVC (Data Version Control)** to ensure reproducibility and scalability, showcasing modern ML workflow best practices.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup Instructions](#setup-instructions)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [Acknowledgments](#acknowledgments)
8. [Future Enhancements](#future-enhancements)

---

## Project Overview

The **Water Potability Prediction** project aims to classify water samples as potable or non-potable based on key physicochemical attributes. By leveraging DVC for data versioning, the project maintains a robust and traceable workflow for:

- Data preprocessing and transformation.
- Training and validating predictive models.
- Experiment tracking and version control for datasets and models.

---

## Features

- **Data Version Control**: Efficiently manage datasets and experiment results using DVC.
- **Data Preprocessing**: Handling missing values, scaling, and transforming data for model readiness.
- **Pipeline Automation**: Seamlessly integrate multiple stages into a reproducible pipeline.
- **Model Evaluation**: Compare models using metrics like accuracy, precision, and recall.
- **Versioned Artifacts**: Store and retrieve model versions and datasets effortlessly.

---

## Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **DVC (Data Version Control)**
- **Matplotlib**, **Seaborn**

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/sadavaidya/Water_potability_with_dvc.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Water_potability_with_dvc
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Initialize DVC:
   ```bash
   dvc init
   ```

5. Pull the dataset and model artifacts using DVC:
   ```bash
   dvc pull
   ```

6. Run the pipeline:
   ```bash
   dvc repro
   ```

---

## Usage

- Add new datasets to the `data/` folder and version them using DVC.
- Modify pipeline stages or configurations in `dvc.yaml`.
- Use DVC to track experiments and compare results.
- Run `python main.py` for custom executions.

---

## Project Structure

```
Water_potability_with_dvc/
├── data/              # Dataset files
├── models/            # Trained models and artifacts
├── src/               # Source code for preprocessing and training
├── config/            # Configuration files for the pipeline
├── dvc.yaml           # DVC pipeline definition
├── main.py            # Entry point for custom execution
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation
```

---

## Acknowledgments

This project was inspired by industry practices in ML pipeline development and version control. Special thanks to the developers and community behind DVC for their excellent documentation and tools.

---

## Future Enhancements

- Integrate with cloud storage for artifact management.
- Add support for hyperparameter tuning.
- Implement advanced visualization dashboards for model metrics.
- Extend pipeline to support real-time predictions.

---
