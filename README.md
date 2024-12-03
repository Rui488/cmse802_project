# cmse802_project
Project Title: Predicting Plant Uptake of Per- and Polyfluoroalkyl Substances (PFAS) from Hydroponics Using Machine Learning Models

## Brief Description:
This project utilizes machine learning to predict the root uptake of PFAS by plants in hydroponic systems. The goal is to understand key factors influencing PFAS uptake and to offer insights into PFAS bioavailability in crops, crucial for environmental risk assessment and food safety.

## Project Objectives:
1. Master data preprocessing techniques to enhance data quality.
2. Learn model tuning methods to achieve optimal parameter settings.
3. Understand the principles and applications of various machine learning models.
4. Develop a high-accuracy predictive model for PFAS uptake in plants.
5. Analyze the performance and applicability of the model in real-world scenarios.

## Repository Structure

The repository is organized into several directories, each with a specific purpose:

1. **codings/**: Contains all the data processing and visualization scripts used in the project, excluding the machine learning models. All scripts are in Jupyter Notebook format (`.ipynb`).

2. **config/**: Holds configuration files for the project, such as settings for machine learning models and data processing parameters.

3. **data/**: Stores the raw and processed data used for the analysis.

4. **models/**: Contains the code for the machine learning models used in the project, as well as log files that document the model tuning process.

5. **results/**: Includes all visualizations (charts, graphs, etc.) and the predicted values output by the machine learning models.

6. **src/**: Houses the source code for any additional scripts or programs used in the project.


## How to Run the Code

To set up and run the code for this project, follow these steps:
1. **Clone the Repository**:
   git clone https://github.com/Rui488/cmse802_project.git
Navigate into the Project Directory:

   cd cmse802_project
2. **Install the Required Dependencies**:
   Use pip to install the necessary packages listed in requirements.txt:

   pip install -r requirements.txt
3. **Run the Data Preprocessing Script**:
Execute the data preprocessing script located in the src/ directory:

   python src/data_preprocessing.py
4. **Train the Models**:
The machine learning models can be trained using the scripts in the models/ directory.

5. **Evaluate Model Performance**:
The performance of the models can be evaluated by reviewing the results stored in the results/ directory.

6. **View Visualizations and Predictions**:
All visualizations and model predictions are available in the results/ directory.