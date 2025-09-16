# ICU-Patient-Management-LSTM
## Project Description

Efficient management of ICU patients and critical care resources is essential in healthcare.
This project builds a predictive model that analyzes patient data and forecasts ICU requirements, helping optimize bed allocation, staff management, and timely intervention.

Problem: ICU resources are limited, and sudden patient influx can cause shortages.

Solution: A predictive system using LSTM-RNN to analyze patient records and predict outcomes, improving ICU management and reducing resource strain.


## Dataset

The dataset used contains patient health records (vitals, lab results, demographics, etc.).

For confidentiality, a simulated / publicly available dataset was used.

Data preprocessing included handling missing values, normalization, and feature engineering.

## Model

Architecture: Long Short-Term Memory (LSTM) Recurrent Neural Network.

Frameworks: TensorFlow / Keras.

Training: Time-series based patient monitoring data.

Output: Predicted patient severity and ICU resource requirement.

## Results

Achieved 93% accuracy on test data.

Effective in predicting ICU requirements and optimizing patient management.

Provides insights for resource allocation in healthcare settings.


##  How to Run

### Google Colab
1. Open the notebook in Google Colab.
2. Install dependencies (TensorFlow, Keras, Pandas, NumPy, Matplotlib, scikit-learn).
3. Upload dataset (if required).
4. Run all cells.

### Jupyter Notebook (Local)
1. Clone this repository:
   git clone https://github.com/Anushabiradar07/ICU-Patient-Management-LSTM.git
   
   cd ICU-Patient-Management-LSTM

3. Install requirements:
   pip install -r requirements.txt
4. Run:
   jupyter notebook ICU_Patient_Management.ipynb
