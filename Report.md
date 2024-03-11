-- Overview --

 Explain the purpose of this analysis.


--Results--
Address the following questions:

Data Preprocessing:

    What variable(s) are the target(s) for your model?

    A: The target variable for the model is 'IS_SUCCESSFUL'

    What variable(s) are the features for your model?

    A: All columns in the dataset except 'IS_SUCCESSFUL' are considered features for the model

    What variable(s) should be removed from the input data because they are neither targets nor features?

    A: The 'EIN' and 'NAME' columns are removed from the input data as they do not provide relevant information for predicting the success of charity applications.

    Compiling, Training, and Evaluating the Model

    How many neurons, layers, and activation functions did you select for your neural network model, and why?

    The model architecture includes two hidden layers with 80 and 30 neurons. ReLU is chosen as the activation function for the hidden layers

    Were you able to achieve the target model performance?

    No
    What steps did you take in your attempts to increase model performance?

    Adding number of layers & neurons, increaseing number of epochs. 

--Summary--
    
In Summary the model tried to increase accuracy by increasing the number of layers and nurons. Wasn't able to significatly increase teh accuracry shown in the model. Furhter exploration  needs to be done to increase accuract. 