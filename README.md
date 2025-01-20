# Leak-Detection-in-Smart-Water-Distribution-System-Using-ANNs
Elements of the Project -
A major chunk of project involved the study of Leakage Detection techniques, and then, conducting experiments on a physical testbed (existing in CSIR-CEERI, Pilani) which has a pipeline network with all relevant sensors installed at various places, which mimics the arrangement of a typical water distribution network. PLC and SCADA system is installed for control and data collection.

Thereafter, data was collected by conducting experiments by simulating various types of leak and studying the behaviour of the system.

Further, the data was carefully analysed to study the dependence of various parameters at various nodes on a leak, and study of how these parameters are interdependent. Further, deciding features were extracted which were to be used as inputs for the classification.

An ANN based model was trained to after carefully deciding the features (which were temperature, pressure, flow rate and vibration at different nodes of the network) which classifies a state of operation as leak or not a leak.

Included Files with the repository -
Data : A portion of used Data to observe the nature
Analysis_and_Model.ipynb : Analysis of Data, Training the model, Testing the model
Feature Dependency -
Only the % dependency of leak on various parameters are shown here. Individual Data Analysis graphs and visualizations can be seen from Visualizations Folder.



Model -


Results -
Metric	Value (%)
Accuracy	92%
Precision	92.5%
Recall	90.7%
F1-score	91.4%
