# Neural_Network_Charity_Analysis

##Overview of the analysis.

The purposes of this analysis was to aplplied the acquired knowledge about deep neural networks to the Alphabet Soup's team regarding the funding program will be created.

For this reason, a dataset was given for analysis which it was cleaned and filtered in order to start compiling, training and evaluating the model.

On the first model applied, 2 hidden layers were created with 80 and 30 neurons respectively. On the first and second layer the RELU activation function was applied while for the output, the sigmoid function gave good results when the model was ran.

Mainly, a checkpoint was created for both models, for the main one and the optimization one in order to save the weights for future uses. After all this, model was evaluated and the HDF5 was saved in the repo as well.

##Results: 

*Data Preprocessing
--Target variable considered for this project was the **Is Successful**, while the remain variables in the dataset depicted here below were considered as features. 
--Features Variables:
----APPLICATION_TYPE—Alphabet Soup application type
----AFFILIATION—Affiliated sector of industry
----CLASSIFICATION—Government organization classification
----USE_CASE—Use case for funding
----ORGANIZATION—Organization type
----STATUS—Active status
----INCOME_AMT—Income classification
----SPECIAL_CONSIDERATIONS—Special consideration for application
----ASK_AMT—Funding amount requested
----IS_SUCCESSFUL—Was the money used effectively

--What variable(s) are neither targets nor features, and should be removed from the input data?
----EIN and NAME—Identification columns

*Compiling, Training, and Evaluating the Model

--Neurons, layers and Activation functions.

On the main model, the accuracy obtained was pretty near the the 75% accuracy target, after applying 2 hidden layers with 80 and 30 neurons respectively. ReLU function applied on the layers and Sigmoid for the output, but still like that target accuracy was not reach because of the lack of training. This topic will be pending to study more in depth this content and reach this goal.

*Summary: 
Despite the target accuracy was not reached, this is a good example for start practicing to get this goal. So, the project will be modeled first in the TensorFlow websit, and later when the results be reached, then apply it to the code here attached.