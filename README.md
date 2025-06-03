# EMG-Based Muscle Movement Detection

This project explores how machine learning can be applied to detect human muscle movement using EMG (electromyography) and accelerometer data.

We used a public dataset from IEEE DataPort titled:  
[Bicep Detection Using Electromyography and 3-Axis Accelerometer Data](https://ieee-dataport.org/documents/bicep-detection-using-electromyography-and-3-axis-accelerometer-data)

## Files in This Repository

- `EMG_Muscle_Analysis.ipynb`: Jupyter notebook using XGBoost, LightGBM, CatBoost, and StackingClassifier
- `Bicep_Detection_Dataset.csv`: The labeled dataset used for classification

## Project Overview

We trained and evaluated multiple ML models to classify movements as either:
- **Correct** (proper bicep curl or action)
- **Incorrect** (wrong muscle activation or movement)

Models used:
- XGBoost
- LightGBM
- CatBoost
- Stacking Classifier

## 🧑‍🤝‍🧑 Collaboration

This project was collaboratively built by our team members:

- [Nusrat Jaben Aurnima](https://github.com/NushratJabenAurnima)
- [Zihad Khan](https://github.com/Zihad107)
- [Shairin Akter Hashi](https://github.com/Shairin207)
- [MD Shahrukh Hossain Shihab](https://github.com/shihab372)

> _Thanks to everyone for their hard work and dedication._

## Results

A separate report will summarize accuracy, confusion matrices, and classification scores for each model (see `RESULTS.md`).

## License

Dataset credit: IEEE DataPort  
Code: Open for academic and research use
