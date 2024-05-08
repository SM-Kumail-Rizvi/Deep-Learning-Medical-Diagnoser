# Medical Diagnoser: Predicting Diseases and Recommending Treatments

## Overview:
The Medical Diagnoser is a deep learning-based project aimed at diagnosing medical conditions based on textual descriptions of patient problems. The model predicts the disease and recommends appropriate medicine for treatment. This project leverages natural language processing (NLP) techniques and deep learning architectures to analyze patient symptoms and provide accurate medical recommendations.

## Features:
**1. Disease Prediction:** The model predicts the disease or medical condition based on the textual description of the patient's problem.                                     
**2. Treatment Recommendation:** Recommends suitable medications or treatments to address the diagnosed disease.                                                              
**3. Deep Learning Approach:** Utilizes advanced deep learning architecture LSTM to process textual data and make accurate predictions.                                            
**4. User-Friendly Interface:** Provides an intuitive interface using Gradio for healthcare professionals and patients to input symptoms and receive recommendations.

## Files:
**medical_diagnoser.ipynb:** Jupyter Notebook containing the code for training the deep learning model and making predictions.
**medical_diagnoser_data.csv:** CSV file containing the dataset with patient problem descriptions, corresponding diseases, and recommended prescriptions.

## Dataset Format:
The dataset file medical_diagnoser_data.csv have the following columns:

**1. Patient_Problem:** Textual description of the patient's problem or symptoms.                                                                                                
**2. Disease:** Corresponding medical condition or disease diagnosed based on the patient problem.                                                                             
**3. Prescription:** Recommended medication or treatment for the diagnosed disease.


## Installation:
**1. Clone the repository:**
      git clone https://github.com/your_username/medical_diagnoser.git 

**2. Navigate to the project directory:**
      cd medical_diagnoser
   
**3. Install the required Python packages:**
      pip install -r requirements.txt

## How to Run:
1. Open the medical_diagnoser.ipynb notebook in Jupyter Notebook or Google Colab.
2. Run the notebook cells to load the dataset, preprocess the data, train the model, and make predictions.
3. Ensure that the medical_diagnoser_data.csv file is in the project directory.
4. Follow the instructions provided in the notebook for data preprocessing, model training, and prediction generation.

## Results:


## Future Enhancements:
**Model Fine-Tuning:** Continuously improve model accuracy by fine-tuning on larger and more diverse datasets.                                                                

**Integration with Electronic Health Records (EHR):** Integrate the model into healthcare systems to assist healthcare professionals in making faster and more accurate diagnoses.                                                                                                                                                                    

**Multimodal Data Integration:** Incorporate additional data sources such as medical images or patient demographics to enhance diagnosis accuracy.

## Contributions:
Contributions to the Medical Diagnoser project are welcome! Whether it's bug fixes, feature enhancements, or dataset improvements, your contributions help advance the capabilities of the model and benefit the healthcare community.

## License
This project is licensed under the MIT License. See the LICENSE file for details.






