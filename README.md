# Machine Learning and Statistics Project
Repository for the final assessment as part of the Higher Diploma in Data Analysis for GMIT

## Description:
This notebook, as part of the assignment, is based on the analysis of the Boston House Prices Data Set, which is a standard of understanding basic Machine Learning principles.

Statistical calculations are performed with Pandas, Scipy and NumPy.
For graphical representation and plotting Seaborn and Matplotlib were used.
The Machine Learning heavylifting was carried out by Keras.

This investigation is organised as follows:

### Description of the data set
Basic understanding of the size, composition and nature of the variables in the dat set, extracting basic information useful for further analytical processes. Basic Pandas python code is used for this purpose, taking advantage of Panda's DataFrame capabilities. 

### Linear regression and 2 sample t test
Using one predictor (independent) variable and the target (dependent) variable, and given their nature (categorical and continous), the investigation consists in the appropriate hytpothesis test, which in this case is the 2 independent samples t test. The purpose of this test is to determine (or not) if these two variables are correlated, meaning that a change in one of them (the predictor, independent variable or feature) will explain a significative amount of change in the other (dependent, target or output variable). Python has several tools that can evaluate this.

### Machine Learning with Keras - Neural Networks for prediction
The third part implies the use of the entire data set to create a neural network, train it and use it to predict the result of the dependent variable.

Keras package is introduced in the notebook and links to the documentation page are also included.

During the development of this section several approaches were taken in consideration prior to obtaining an accurate enough neural network output minimising the error. These approached included the standarisatrion of the variables, which at the end was incorpored into the final model, and the other was a more classic regression approach which was rejected since fell out of the scope of this investigation, but was considered interesting enough to impulse new lines of investigation once this is closed.

## Usage
To run this code, please use the Jupyter Notebook file under the name Boston House Prices Data Set Analysis.ipynb. 

Jupyter Notebook can be initiated through Anaconda Navigator and it will use your browser to deploy both texts an code, as it includes an interpreter.

All code included in this project is Python 3.6.4. Additional packages needed to run this code are:
- NumPy
- Pandas
- Scipy
- Keras
- Seaborn
- Matplotlib


All this packages can be individually downloaded and installed as per instructions available in their documentation. However, dowloading an installing [Anaconda](https://www.anaconda.com/download/) will ensure full compatibility for Linux, Mac and Windows systems. 

**NOTE**: Keras is not included by default in Anaconda, but adding it is a quite simple task. For the completion of this workbook, Keras and TensorFlow were installed through Conda, as explained in [this link](https://medium.com/@margaretmz/anaconda-jupyter-notebook-tensorflow-and-keras-b91f381405f8)

## Resources used
Along this project, several sources of information have been used. Although specific references are included as links in the notebook, the main reference sources have been:
- [StackOverflow](https://stackoverflow.com/)
- [NumPy and SciPy Documentation](https://docs.scipy.org/doc/)
- [MatPlotLib documenttion](https://matplotlib.org/)
- [Stats Trek](https://www.stattrek.com/)
- [Keras Documentation](https://keras.io/)
- [Machine Learning Mastery](https://machinelearningmastery.com/)
- [Medium](https://medium.com/@thevie/predicting-boston-housing-prices-step-by-step-linear-regression-tutorial-from-scratch-in-python-c50a09b70b22)
- [MarkTechPost](https://www.marktechpost.com/)

## License
This project is under GNU General Public License v3.0
