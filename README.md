# Iris-Species-Machine-Learning
To classify iris plants into three species in a given dataset

# Dataset
[UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Iris)

## Attribute Information
1. sepal length in cm
2. sepal width in cm
3. petal length in cm
4. petal width in cm
5. class:
    - Iris Setosa
    - Iris Versicolour
    - Iris Virginica

# How to Run This Program
1. To install Python3 virtual environment:
    1) Makde a directory and run the following lines inside the directory: 
        - `python3 -m pip install --user -U pip`
        - `python3 -m pip install --user -U virtualenv`
        - `virtualenv env`    
    2) To invoke the environment, type: 
        - `source env/bin/activate`
            - to deactivate, run: 
               - `deactivate`
    3) To install required modules and their dependencies, type: 
        - `python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn seaborn`
        - To check your installation, type: 
            - `python3 - c "import jupyter, matplotlib, numpy, pnadas, scipy, sklearn, seaborn"`
               - There should be no output and no error
2. To fire up Jupyter, type: 
    - `jupyter notebook`
    - If facing notebook error such as "... no web browser found: could not  locate runnable browser.", type:
        - `jupyter notebook --no-browser`
