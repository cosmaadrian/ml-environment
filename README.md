# Machine Learning virtual environment

Follow the below steps to setup your machine for data science!


## 1. Install conda
  
  Conda is a popular package manager for python, to help you create environments and manage libriares.
  
  You can find conda installers at the following link, for both Windows and Linux:
  
  https://conda.io/docs/user-guide/install/windows.html?highlight=conda
  
  Refer to [this](https://conda.io/docs/user-guide/cheatsheet.html) cheet sheet for the most popular commands.
  
## 2. Create virtual environment

  To create your virtual environment with all the necessary packages, simply paste this into terminal / command line:
  
  ```conda create --name <environment_name> python=3.6 scipy pandas scikit-learn jupyter matplotlib tensorflow keras```
  
## 3. Activate the virtual environment

  Before doing anything, make sure to activate the virtual environment:
  
  For Linux:
  ``source activate <environment_name>``
  
  For Windows:
  ```activate <environment_name>```
  
## 4. Missing packages

  If you ever need any new packages, you can install them within your environment with:
  
  ```conda install <package_name>```
  
## 5. ??
## 6. Profit
