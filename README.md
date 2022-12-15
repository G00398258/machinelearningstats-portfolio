# Machine Learning & Statistics Portfolio    
***  
**Student Name:** Gillian Kane-McLoughlin  | **Student Number:** G00398258  


### Description  
***
This repository will contain all components of the assessment for the Machine Learning & Statistics module for Winter 2022.  

The contents are as follows:  
- time-series-anomaly.ipynb - this is the Jupyter notebook for the machine learning project piece of the assessment  
- this README.md file  
- requirements.txt - text file listing all the Python modules & libraries required to run the two notebooks  
- a .gitignore (Python) file  
- data folder containing files used and generated over the course of completing this assessment 
- 'Exercises' folder containing three Jupyter notebooks for the regular tasks completed over the course of this module  


### Software Information
***
The code for this assignment was written in Python (version 3.8.8) and ran in Jupyter Lab.    

Jupyter Version:  
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

Please see the requirements.txt file in this repository for information on the modules and libraries used.  


### How to Run the Notebooks 
***
A Python environment is required to run the two Jupyter notebooks containing the bulk of the submission for this assessment. To ensure that the notebooks run correctly, I would advise that you first install Anaconda on your machine, clone this repository to your device and then open and run the notebooks in Jupyter Lab as per the steps below:  
- Download Anaconda from https://www.anaconda.com/products/individual  
- Install the package  
- Clone this repository to your machine as per the steps outlined [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)    
- Open the command line interface (CLI) on your machine - on Windows, open the Command Prompt tool by selecting Start, searching "cmd" and selecting it from the list. On a Mac, click the Launchpad icon in the Dock, type "Terminal" in the search field, then click Terminal  
- Navigate to the folder where the repository was cloned (above) on the CLI using the cd (Change Directory) command  
- Once in the correct folder, enter command "jupyter lab" to launch the program (note that although Jupter launches in your browser, it is running on your local machine)  
- Select the desired notebook from the left hand pane (cao.ipynb or pyplot.ipynb)  
- **Important:** Select "Kernel" at the top of the notebook and click "Restart Kernel and Run All Cells"  
- To exit Jupyter once finished, close your browser, return to the CLI and enter command CTRL+C  


### What's in the Notebooks? NEEDS TO BE UPDATED!!
***
**CAO Notebook**  
This Jupyter notebook contains an overview of how to load CAO points information from the CAO website into a pandas data frame, a detailed comparison of level 8 CAO points in 2019, 2020, and 2021 and some plots to enhance the viewer experience.    

The notebook is broken down into four sections:  
- Section 1: Loading the CAO Points into Pandas Dataframes  
- Section 2: Creating a Single CAO Points Dataframe Using Concat & Join  
- Section 3: Defining a Function to Perform the Analysis  
- Section 4: Analysing CAO Points  

The results observed in Section 4 show an increase in overall CAO points in 2021 compared to 2020, both in terms of the courses with the highest points and in both the mean and medium points ranges, as shown in the plots generated.  

Throughout the course of compiling this notebook I faced many difficulties, initially with loading the points into dataframes, but particularly in working with the CAO points data, as the information provided was quite messy and not easily comparable. I attempted to tidy this data up as much as possible, but I have to acknowledge that in doing this I did lose some data, resulting in a less accurate analysis. However, despite these difficulties, the analysis undertaken did show an overall increase in CAO points in 2021 across all the measurements observed, which is what I expected to see at the outset of this project.  

**Pyplot Notebook**  
This Jupyter Notebook provides a clear and concise overview of the Matplotlib.Pyplot package in Python, as well as an in-depth explanation of the following plots from the package:    
1. Pie Charts  
2. Scatter Plots  
3. Stack Plots  

In each case, I provide an explanation of what each of these plots are, what they are used for, the syntax and parameters required to plot them, and a practical example of each plot using real world data.  

A different style is used for each plot. Note that you can check what styles are available and change the styles on any of the plots using the following commands: 

``# To check what styles are available``  
``print(plt.style.available)``  

``# To change the style``  
``plt.style.use('style_name')``  

### References & Data Sources  
***
**_Statistics Exercises_**  
 https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.fisher_exact.html  
 https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html  
 https://github.com/ianmcloughlin/2223-S1-machine-learn-stats/tree/main/notebooks  
 https://unstats.un.org/unsd/business-stat/  

**_Models Exercises_**  
https://www.bradthiessen.com/html5/docs/ols.pdf  
https://www.coursera.org/learn/fitting-statistical-models-data-python  
https://docs.scipy.org/doc/numpy-1.6.0/reference/generated/numpy.absolute.html  
https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.curve_fit.html  
https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html#scipy.optimize.minimize  
https://github.com/ianmcloughlin/2223-S1-machine-learn-stats/tree/main/notebooks  
https://numpy.org/doc/stable/reference/generated/numpy.asarray.html  
https://stats.stackexchange.com/questions/118/why-square-the-difference-instead-of-taking-the-absolute-value-in-standard-devia  

**_Parameters Exercises_**  
https://github.com/ianmcloughlin/2223-S1-machine-learn-stats/tree/main/notebooks  
https://mathcracker.com/  
https://mathinsight.org/function_machine_parameters  
https://numpy.org/doc/stable/reference/generated/numpy.asarray.html  
https://undergroundmathematics.org/  

# End  
***