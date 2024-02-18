Title: Predicting Rain

Project Description:

This project aims to develop a machine learning model to predict rain. This information can be crucial for:

A rain prediction model holds significant practical applications in various domains. One key application is in agriculture, where farmers can use accurate rain predictions to optimize irrigation schedules and plan planting and harvesting activities, leading to improved crop yields. Additionally, the model can be valuable for water resource management, aiding in reservoir planning and flood control. In urban planning, it can enhance infrastructure resilience by providing insights into potential drainage issues during heavy rainfall. For transportation and logistics, the model can contribute to safer and more efficient routing by anticipating adverse weather conditions. Moreover, it can benefit individuals by offering timely information for planning outdoor activities, events, or travel. Overall, a reliable rain prediction model can have widespread positive impacts on resource allocation, risk mitigation, and day-to-day decision-making across various sectors.

Dataset: Australian weather dataset.

Data source: The original source of the data is Australian Government's Bureau of Meteorology and the latest data can be gathered from http://www.bom.gov.au/climate/dwo/.
The dataset to be used has extra columns like 'RainToday' and our target is 'RainTomorrow', which was gathered from the Rattle at https://bitbucket.org/kayontoga/rattle/src/master/data/weatherAUS.RData
This dataset contains observations of weather metrics for each day from 2008 to 2017.

Methodology:

Machine learning models: Three models were used namely, Logistic Regression, SVC, and Decision Tree Classifier and the best performing model was selected among them.
Evaluation metrics:We used the metric - Accuracy Score, Jaccard Index, F1 Score and Log Loss.
Model training and hyperparameter tuning: We trained the models using some parameters.

Model performance: The best performing model in this case was Decision Tree Classifier which had an accuracy score of 0.82.
