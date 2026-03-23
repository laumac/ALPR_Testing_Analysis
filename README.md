# ALPR System Accuracy Analysis (Lund Case Study)

## Project Overview
This project is a Quality Assurance (QA) focused analysis of an **Automatic License Plate Recognition (ALPR)** system. Using Python and Pandas, I evaluated the system's precision in vehicle identification under various conditions.

## Objectives
* **Evaluation of system precision:** Comparing real license plates against AI-recognized data.
* **Edge Case Testing:** Identifying failure points (e.g., "NO_READ" or misread characters like 'Z' vs '2').
* **Data Validation:** Ensuring data integrity using automated Python scripts.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas (for data manipulation and accuracy metrics)
* **Environment:** Google Colab / Jupyter Notebooks

## Key Testing Metrics
- **True Positives:** Correctly identified plates.
- **False Positives:** Misidentified characters.
- **Failure to Read:** Scenarios where the algorithm produced no output.

---
*Developed by Laura Macioniene as part of a transition into Software Quality Engineering.*
