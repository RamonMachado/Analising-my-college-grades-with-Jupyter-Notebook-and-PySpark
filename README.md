# Analyzing my college grades with Jupyter Notebook and PySpark

The main goal of this project is to just practice a little bit of PySpark combined with Jupyter and Pandas. There’s nothing that much incredible here, I just read a csv file with my grades to a Spark Dataframe and use it to calculate some data. Then I plot a few graphs with Pandas. All of this running on a Jupyter Notebook.

## Dependencies
- Python 3.7+
- Virtualenv 16.7.9+

## Installation and Execution

In the main directory just run the makefile. It will create the virtual environment, install PySpark, Jupyter and Pandas.
You can run it by typing in your terminal:

```
$ make install
```

Before running you need to also set two environment variables in your terminal (you can save it in your bash file so you won't need to type it again after rebooting your machine):

```
$ export PYSPARK_DRIVER_PYTHON='jupyter'
$ export PYSPARK_DRIVER_PYTHON_OPTS='notebook'
```

To run, first you need to start your virtual environment by typing:

```
$ source venv/bin/activate
```

And then you need to start pyspark on your terminal by typing:

```
$ venv/bin/pyspark
```

It will start PySpark and open the Jupyter interface in your browser. Choose the “my_grades_notebook.ipynb” from the main project folder and feel free to play with it :)

If you want to finish the application, press "Ctrl+C" on your terminal where pyspark is running. It will prompt you to press "y" to confirm.
To deactivate the venv just type "deactivate" on your terminal where the venv is running.


## Uninstall

To uninstall the venv, just open the terminal and type:

```
$ make clean
```

