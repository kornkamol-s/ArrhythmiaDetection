---------------------------------------------------------
  Folder Structure
---------------------------------------------------------
|-- models/                                            # Saved trained models for evaluation
|   |-- svm/
|   |-- cnn/
|-- source/                                             # Source dataset
|   |-- mitbih_test.csv					# Test data
|   |-- mitbih_train.csv				# Train data (not included in zip file)
|-- Training.ipynb                                      # Inital data analysis, grid search and model trainings
|-- Testing.ipynb                                       # Models evaluation
|-- Tools.ipynb                                         # All functions related to training and evaluating models
|-- requirements.txt                                    # Libraries and Dependencies


---------------------------------------------------------
Setup Instructions
---------------------------------------------------------
1. Extract all the files from the zip file
2. Change directory (cd) to the extracted folder
3. Create a new virtualenv:

virtualenv Student_env
cd Student_env
Scripts\activate
cd ..

4. Install packages:

pip install -r requirements.txt

5. Execute this code to open the IPYNB file:
jupyter notebook test.ipynb