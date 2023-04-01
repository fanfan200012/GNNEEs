GNNEEs

The Graph neural network(GNN) model with developed applicability domain(AD) methods could contribute to effective EEs screening

Fan Fan, Gang Wu, Yining Yang, Yuli Qian, Fu Liu, Qingmiao Yu, Hongqiang Ren, Jinju Geng.Manuscript to be submitted.

Introduction
We developed a standalone software called GNNEEs via the python package auto-py-to-exe for prediction of potential environmental estrogens(EEs). The GNN model and AD calculation were encapsulated in this software. 

Guidance
Two functions are available in this software: reliable prediction and explainable prediction for a compound of interest. Users can select either function by clicking on it and then clicking the ‘OK’ button. If the ‘prediction’ function is chosen, the users need to select the input path and file for the compounds of interest. The file should be saved in TXT format, with a column titled ‘SMILES’ listing the SMILES of each compound. After selecting the file, the user can click the ‘Submit’ button to obtain predicted results with AD indicators, which can help judge the reliability of the prediction. The predicted results will be saved to a CSV format file in the selected input path.
If the ‘feature visualization’ function is selected, the users need to enter the SMILES of a compound and click the ‘Submit’ button. This will generate a feature visualization of the input compound, highlighting critical substructures related to estrogenic agonist activity. Additionally, the feature visualization plots of similar compounds in the training set will be displayed simultaneously in the window, helping the user to better understand the model's prediction.


Document Description
ER_app.txt: Input files for demonstration purposes
df_predict.csv: Output files for demonstration purposes
GNNEEs-Help.pdf: Instructions on how to use GNNEEs
GNNEEs.zip: the software, unzip it and run the GNNEEs.exe file directly

Developer Information
Maintainer:Dr.Fan, Professor Geng
Contact US:fanfan20201031@163.com
State Key Laboratory of Pollution Control and Resource Reuse, School of the Environment, Nanjing University, Nanjing 210023, Jiangsu, PR China