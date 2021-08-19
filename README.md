# Tiny-ML IR-Sensor

The source code for building a machine learning model is presented below. The model is created in Python using Colab. Follow the introduction video linked below to get a first impression of Colab. If you need further information check out the following link: https://towardsdatascience.com/getting-started-with-google-colab-f2fff97f594c 
You can also train the model in an equivalent local environment. 

## Data Preparation 

1) Get to know the data 

    The dataset was created with an IR-Temperature sensor which generates an 8x8 array with temperature values. All values are recorded in degrees celsius. 
    As an input we use a timestamp as well as 64 temperature values and the label. We decided to set the number of classes to two. 
    
    Class 0 describes the state ok.                                 Class 1 describes a critical state.  
