# Parkinson-s-Disease-Detection-Project
Overview
This repository contains the code and documentation for the Parkinson's Disease Detection project, focusing on exploratory data analysis (EDA) using the Oxford Parkinson's Disease Detection Dataset. The project aims to analyze biomedical voice measurements to discriminate between healthy individuals and those with Parkinson's disease.

Dataset
The dataset used in this project is the Oxford Parkinson's Disease Detection Dataset. It comprises a range of biomedical voice measurements from 31 individuals, 23 of whom have Parkinson's disease. Each row represents a voice recording, with various voice measures as attributes. The primary task is to differentiate healthy individuals from those with Parkinson's disease based on the provided voice measurements.

Data Set Characteristics:

Nature: Multivariate
Number of Instances: 197
Area: Life
Attribute Characteristics: Real
Number of Attributes: 23
Date Donated: 2008-06-26
Associated Tasks: Classification
Missing Values: N/A
Source:

The dataset was compiled by Max Little of the University of Oxford in collaboration with the National Centre for Voice and Speech, Denver, Colorado.
Citation Request:

If you use this dataset, please cite the following paper:
'Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection', Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM. BioMedical Engineering OnLine 2007, 6:23 (26 June 2007)
Project Structure
data/: Contains the Parkinson's Disease dataset file (parkinsons_data.csv).
notebooks/: Jupyter notebooks for data analysis and visualization.
01_data_preparation.ipynb: Data loading and preparation.
02_exploratory_data_analysis.ipynb: Exploratory Data Analysis (EDA) tasks.
README.md: Project overview, setup instructions, and usage guidelines.
LICENSE: MIT License for the project.
Requirements
Python 3.x
Jupyter Notebook
pandas
numpy
matplotlib
seaborn
Setup
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/briankibe450/parkinsons-disease-detection.git
Navigate to the project directory:
bash
Copy code
cd parkinsons-disease-detection
Install the required Python dependencies:
Copy code
pip install -r requirements.txt
Usage
Open the Jupyter notebooks in the notebooks/ directory.
Follow the step-by-step instructions in the notebooks to perform data analysis and visualization tasks.
Explore the insights and trends in the Parkinson's Disease dataset.
Modify the code or experiment with different analysis techniques as needed.
Contributing
Contributions to improve the project are welcome! If you find any issues or have suggestions for enhancements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Max Little and the National Centre for Voice and Speech, Denver, Colorado, for providing the Parkinson's Disease Detection Dataset.
