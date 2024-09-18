# stepwise-regression-SWQP-khadakwasala
This repository contains a Python implementation of stepwise regression with k-fold cross-validation for analyzing Surface Water Quality Parameters  in water samples from Khadakwasala. The Surface Water Quality Parameters including Turbidity, Chlorophyll, Dissolved Oxygen, Biochemical Oxygen Demand, Chemical Oxygen Demand. 

Water Quality Analysis - Khadakwasala Reservoir
This repository contains Python implementations of stepwise regression with k-fold cross-validation for analyzing various water quality parameters in samples from Khadakwasala Reservoir.
Overview
The project aims to model and predict different water quality parameters using stepwise regression techniques. Each parameter has its own Jupyter notebook for detailed analysis.
Parameters Analyzed

Biochemical Oxygen Demand (BOD)
[Other parameter 1]
[Other parameter 2]
[Add more parameters as applicable]

Features

Stepwise regression algorithm for feature selection
K-fold cross-validation to ensure model robustness
Akaike Information Criterion (AIC) for model evaluation
Handling of NaN and infinite values in datasets
Generation of summary statistics and model coefficients
Prediction of parameter values using trained models

Repository Structure
Copy├── README.md
├── data/
│   └── [input data files]
├── notebooks/
    ├── Stepwise_Regression_Turbidity-K-Fold-Khadakwasala.ipynb 
│   ├── Stepwise_Regression_Chlorophyll_Khadakwasala-K-Fold.ipynb
│   ├── Stepwise_Regression_DO_Khadakwasala-K-Fold.ipynb
│   ├── Stepwise_Regression_BDO_Khadakwasala-K-Fold.ipynb
│   └── Stepwise_Regression_CDO_Khadakwasala-K-Fold.ipynb

├── output/
│   └── SWR_Result_Khadakwasala_Turbidity.PNG
    └── SWR_Result_Khadakwasala_Chlorophyll.PNG
    └── SWR_Result_Khadakwasala_DO.PNG
    └── SWR_Result_Khadakwasala_BOD.PNG
    └── SWR_Result_Khadakwasala_CDO.PNG
└── requirements.txt
************************************
Dependencies
***********************************
pandas
numpy
statsmodels
scikit-learn

Install all dependencies using:
Copypip install -r requirements.txt
Usage

Clone this repository:
Copygit clone [[repository URL](https://github.com/rpkulkarni/stepwise-regression-SWQP-khadakwasala.git)]



Install the required dependencies:
Copypip install -r requirements.txt

Open the Jupyter notebook for the parameter you want to analyze:
Copyjupyter notebook notebooks/[Notebook name].ipynb

Follow the instructions within each notebook to run the analysis.

Outputs
Each notebook generates several outputs:

A list of selected features for the parameter
Summary statistics of the best model
Coefficients and equation of the multiple linear regression model
Original and predicted parameter values
An Excel file with original and predicted values

Output files are saved in the output/ directory.
Customization
To analyze your own data:

Place your input CSV files in the data/ directory.
Update the file paths in the notebooks to point to your input files.
Modify the target variable and feature selection as needed.

Contributing
Contributions to improve the analysis or extend it to other water quality parameters are welcome. Please follow these steps:

Fork the repository
Create a new branch (git checkout -b feature-branch)
Make your changes and commit (git commit -am 'Add some feature')
Push to the branch (git push origin feature-branch)
Create a new Pull Request

License
[Specify your chosen license here]
Contact
[Dr. Rushikesh Kulkarni: rushikeshk@sitpune.edu.in]
Acknowledgements

[Any acknowledgements or credits you want to include]
