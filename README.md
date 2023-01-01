# Machine Learning & Statistics Portfolio    
***  
**Student Name:** Gillian Kane-McLoughlin  | **Student Number:** G00398258  
<br>  
  
### Description  
***
This repository will contain all components of the assessment for the Machine Learning & Statistics module (Winter 2022).  <br>  
  
The contents are as follows:  
- Exercises - subfolder containing the below three Jupyter notebooks for the regular tasks completed over the course of this module:  
    - 01-statistics-exercises.ipynb  
    - 02-models-exercises.ipynb  
    - 03-parameters-exercises.ipynb  
- .gitignore   
- README.md  
- keras-time-series-anomaly.ipynb - Jupyter notebook containing the machine learning project piece of the assessment  
<br>  
  
### Software Information
***
The code for this assignment was written in Python (version 3.8.8) and compiled in Jupyter Lab.  
<br>  
  
__Jupyter Version:__  
jupyter core : 4.7.1  
jupyter-notebook : 6.3.0  
qtconsole : 5.0.3  
ipython : 7.22.0  
ipykernel : 5.3.4  
jupyter client : 6.1.12  
jupyter lab : 3.0.14  
nbconvert : 6.0.7  
ipywidgets : 7.6.3  
nbformat : 5.1.3  
traitlets : 5.0.5  
<br>  
  
### How to Run the Notebooks 
***
A Python environment is required to run the Jupyter notebooks in this repository. To ensure that the notebooks run correctly, I would advise that you first install Anaconda on your machine, clone this repository to your device and then open and run the notebooks in Jupyter Lab as per the steps below:  
- Download Anaconda from https://www.anaconda.com/products/individual  
- Install the package  
- Clone this repository to your machine as per the steps outlined [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)    
- Open the command line interface (CLI) on your machine - on Windows, open the Command Prompt tool by selecting Start, searching "cmd" and selecting it from the list. On a Mac, click the Launchpad icon in the Dock, type "Terminal" in the search field, then click Terminal  
- Navigate to the folder where the repository was cloned (above) on the CLI using the cd (Change Directory) command  
- Once in the correct folder, enter command "jupyter lab" to launch the program (note that although Jupter launches in your browser, it is running on your local machine)  
- Select the desired notebook from the left hand pane (.ipynb files)  
- **Important:** Select "Kernel" at the top of the notebook and click "Restart Kernel and Run All Cells"  
- To exit Jupyter once finished, close your browser, return to the CLI and enter command CTRL+C  
<br>  
  
### What's in the Notebooks?  
***
**__Keras Notebook__**  
This Jupyter notebook contains a walkthrough of the example code on the [Keras website](https://keras.io/examples/timeseries/timeseries_anomaly_detection/) for timeseries anomaly detection using an autoencoder.   
<br>  
  
In this notebook, I break down and explain the example code in four sections:  
1. Data - in which I gather the data for the project  
2. Pre-Processing - where I prepare the data for use in my model  
3. Neural Network - here I buid, compile and train the model   
4. Evaluation - finally I use the model to make predictions and identify anomalies in the data  
<br>  
  
The results observed in Section 4 show that the model can successfully identify anomalies in the dataset used in this project. In my conclusion, I suggest ways in which the model could possibly be improved, and my thoughts on the project overall.  
<br>  
  
**_Exercise Notebooks_**  
The 'Exercises' subfolder in this repository contains three Jupyter Notebooks in which I have completed the regular tasks for this module found in the statistics, models and parameters notebooks in the [Notebook's subfolder](https://github.com/ianmcloughlin/2223-S1-machine-learn-stats/tree/main/notebooks) of the lecturer's GitHub repository.  
<br>  
  
__Contents:__  
- 01-statistics-exercises.ipynb  
- 02-models-exercises.ipynb  
- 03-parameters-exercises.ipynb  
<br>  
  
The question/instructions for each exercise has been copied into the relevant notebook, and all sources referred to or consulted can be found in the __References & Data Sources__ section below.  
<br>  
  
### References & Data Sources  
***
**_Keras Notebook_**  
https://coolconversion.com/math/scientific-notation-to-decimal/Convert_4.1E-15_to-number  
https://data-flair.training/blogs/keras-loss-functions/  
https://fintelics.medium.com/everything-you-need-to-know-about-numenta-anomaly-benchmark-nab-b43ab7f014df  
https://github.com/ianmcloughlin/2223-S1-machine-learn-stats/blob/main/notebooks/05-evaluation.ipynb  
https://www.kaggle.com/code/residentmario/keras-optimizers  
https://www.kaggle.com/datasets/boltzmannbrain/nab  
https://keras.io/api/callbacks/early_stopping/  
https://keras.io/api/models/model_training_apis/  
https://keras.io/examples/timeseries/timeseries_anomaly_detection/  
https://keras.io/api/layers/core_layers/input/  
https://kitchell.github.io/DeepLearningTutorial/4cnnsinkeras.html  
https://machinelearningmastery.com/adam-optimization-algorithm-for-deep-learning/  
https://machinelearningmastery.com/dropout-regularization-deep-learning-models-keras/  
https://machinelearningmastery.com/how-to-choose-loss-functions-when-training-deep-learning-neural-networks/  
https://machinelearningmastery.com/lstm-autoencoders/  
https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.legend.html  
https://medium.com/towards-artificial-intelligence/autoencoder-for-anomaly-detection-using-tensorflow-keras-7fdfa9f3ad99  
https://neptune.ai/blog/keras-loss-functions  
https://www.projectpro.io/recipes/what-is-drop-out-rate-keras  
https://raw.githubusercontent.com/numenta/NAB/master/data/artificialNoAnomaly/art_daily_small_noise.csv  
https://raw.githubusercontent.com/numenta/NAB/master/data/artificialWithAnomaly/art_daily_jumpsup.csv  
https://towardsdatascience.com/time-series-of-price-anomaly-detection-with-lstm-11a12ba4f6d9  
https://www.tutorialspoint.com/keras/keras_layers.htm  
https://www.tutorialspoint.com/keras/keras_model_compilation.htm  
https://www.tutorialspoint.com/keras/keras_models.htm  
https://wandb.ai/ayush-thakur/dl-question-bank/reports/Keras-Layer-Input-Explanation-With-Code-Samples--VmlldzoyMDIzMDU  
<br>  
  
**_Statistics Exercises_**  
 https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.fisher_exact.html  
 https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html  
 https://github.com/ianmcloughlin/2223-S1-machine-learn-stats/tree/main/notebooks  
 https://unstats.un.org/unsd/business-stat/  
<br>  
  
**_Models Exercises_**  
https://www.bradthiessen.com/html5/docs/ols.pdf  
https://www.coursera.org/learn/fitting-statistical-models-data-python  
https://docs.scipy.org/doc/numpy-1.6.0/reference/generated/numpy.absolute.html  
https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.curve_fit.html  
https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html#scipy.optimize.minimize  
https://github.com/ianmcloughlin/2223-S1-machine-learn-stats/tree/main/notebooks  
https://numpy.org/doc/stable/reference/generated/numpy.asarray.html  
https://stats.stackexchange.com/questions/118/why-square-the-difference-instead-of-taking-the-absolute-value-in-standard-devia  
<br>  
  
**_Parameters Exercises_**  
https://github.com/ianmcloughlin/2223-S1-machine-learn-stats/tree/main/notebooks  
https://mathcracker.com/  
https://mathinsight.org/function_machine_parameters  
https://numpy.org/doc/stable/reference/generated/numpy.asarray.html  
https://undergroundmathematics.org/  
<br>  
  
## End  
***