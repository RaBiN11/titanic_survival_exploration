Project 0: Getting Started and Foundation
Forecast Titanic passenger survival rate
Installation requirements
This project requires Python 2.7 and installs the following python libraries.

NumPy
Pandas
Matplotlib
Scikit-learn
You also need to install and run Jupyter Notebook.

Youda Student City recommends that students install Anaconda, a Python distribution that contains all the libraries and software needed for the project. Here is how to install Anaconda.

If you are using the macOS system and are familiar with the command line, you can install homebrew, as well as the brew version of python.

$ brew install python
Then use the following command to install the required python library.

$ pip install numpy pandas matplotlib scikit-learn scipy jupyter
Code
The core code is in the titanic_survival_exploration.ipynb file, and the helper code is in the titanic_visualizations.py file. Although you have provided some code to help you get started, you still need to add some code to make the functions required by the project successful.

run
On the command line, make sure the current directory is at the top of the titanic_survival_exploration/ folder (the directory contains this README file) and run the following command:

$ jupyter notebook titanic_survival_exploration.ipynb
This will launch Jupyter Notebook to open the project file in your browser.

Students who are unfamiliar with jupyter can look at these two links:

Jupyter uses video tutorials
Why use jupyter?
data
The data for this project is contained in the titanic_data.csv file. The file contains the following characteristics:

Survived: Whether it is alive (0 means no, 1 means yes)
Pclass: social class (1 represents the upper class, 2 represents the middle class, 3 represents the lower class)
Name: The name of the passenger on board
Sex: the gender of the passenger on board
Age: age of the passenger on board (may be NaN)
SibSp: Number of siblings and spouses on board the passengers
Parch: Number of parents and children on board the ship
Ticket: the number of the passenger ticket
Fare: the cost paid by the passenger for the ticket
Cabin: the number of the cabin where the passenger is located (may be NaN)
Embarked: the port where passengers board the ship (C stands for boarding from Cherbourg, Q stands for boarding from Queenstown, and S stands for boarding from Southampton)
