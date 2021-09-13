# ShinyApp

Repository with the application script and the example files used to test the app.
This project has been made in the framework of the subject of model evaluation, display and monitoring at Data Science Degree in Polytechnic University of Valencia. So, it have not an advance scripting level.

The application itself gets a .csv or .arff file with the following conditions:

- The file must be a dataset where the rows are individuals and the columns the attributes of these individuals, with the last column must be a binary attribute, in a character factor format (ex.: "good"/"bad" instead 1/0).
- The data must have been cleaned, without missing values. 

Once the file is given, the user can select a classification method within a list and start the creation of the model. When the process ends, shows a graph with the [ROC curve](https://en.wikipedia.org/wiki/Receiver_operating_characteristic) with a 5-fold cross-validation and the area under the curve (AUC).

In addition, it is possible to submit an instance (individual/row) of the given dataset in .csv format, without the class label, to make predictions and show a weight plot to explain which attributes support and contradict the conclusion.

In the following link you can see how the online app works.
[https://datascience-edm.shinyapps.io/ShinyApp_EDM/](https://datascience-edm.shinyapps.io/ShinyApp_EDM/)


