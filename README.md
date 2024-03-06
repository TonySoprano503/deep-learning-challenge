Overview:
The purpose of this analysis is focused on optimizing a neural network model. The analysis is aimed at refining a neural network's ability to predict or classify based on given input data.

Results
Data Preprocessing
•	Target Variable(s) for the Model:
o	The target variable identified for the model is the "Is-Successful" column.
•	Feature Variable(s) for the Model:
o	The features for the model include NAME, APPLICATION, TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, STATUS, and ASK_AM.
•	Variable(s) Removed from the Input Data:
o	Variables removed from the input data because they are neither targets nor features include EIN, SPECIAL_CONSIDERATIONS, and STATUS.

Compiling, Training, and Evaluating the Model
•	Neurons, Layers, and Activation Functions:
o	The model selected includes three hidden layers. The 2nd and 3rd activation functions were changed to 'sigmoid' to help boost accuracy.
•	Achievement of Target Model Performance:
o	Yes, the target model performance was achieved.
•	Steps Taken to Increase Model Performance:
o	To enhance model performance, the NAME column was converted into data points. Additionally, a third layer was added, and 'sigmoid' activation functions were used for the 2nd and 3rd layers.


Summary
These results suggest that the analysis focused on refining a neural network model by adjusting its architecture and processing features, achieving in improved performance. The specific steps taken to preprocess data, configure the model, and optimize its performance offer valuable insights into the iterative process of developing and tuning neural networks.

