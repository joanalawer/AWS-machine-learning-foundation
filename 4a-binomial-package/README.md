# Exercise: Binomial class

In this exercise, you'll extend the distributions package with a new class called Binomial.

In the Supporting materials section of this page, there is a .zip file called called 4a_binomial_package.zip. Download and unzip this file.

Inside the folder called 4a_binomial_package, there is another folder and these files:

distributions, which contains the code for the distributions package including Gaussiandistribution.py and Generaldistribution.py code.

setup.py, a file needed for building Python packages with pip.

test.py unit tests to help you debug your code.

numbers.txt and numbers_binomial.txt, which are data files used as part of the unit tests.

Binomialdistribution.py and Binomialdistribution_challenge.py. 

Choose one of these files for completing the exercise. Binomialdistribution.py includes more of the code already set up for you. In Binomialdistribution_challenge.py, you'll have to write all of the code from scratch. Both files contain instructions with TODOS to fill out.
In these files, you only need to change the following:

__init__.py, inside the distributions folder. You need to import the binomial package.
Either Binomialdistribution.py or Binomialdistribution_challenge.py You also need to put your Binomialdistribution.py file into the distributions folder.
When you're ready to test out your code, follow these steps:

pip** install your distributions package**. In the terminal, make sure you are in the 4a_binomial_package directory. If not, navigate there by entering the following at the command line:

### cd 4a_binomial_package
### pip install 

Run the unit tests. Enter the following.

### python -m unittest test

Modify the Binomialdistribution.py code until all the unit tests pass.

If you change the code in the distributions folder after pip installing the package, Python will not know about the changes.

When you make changes to the package files, you'll need to run the following:


### pip install --upgrade 
