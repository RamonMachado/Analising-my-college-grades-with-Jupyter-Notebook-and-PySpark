# Analyzing my college grades with Jupiter Notebook and PySpark

The main goal of this project is to just practice a little bit of PySpark combined with Jupyter and Pandas. There’s nothing that much incredible here, I just read a csv file with my grades to a Spark Dataframe and use it to calculate some data. Then I plot a few graphs with Pandas. All of this running in a Jupyter Notebook.

## Dependencies
- Python 3.7+
- Virtualenv 16.7.9+

## Instalation and Execution

In the main directory just run the makefile. It will create the virtual environment, install PySpark, Jupyter and Pandas.
You can run it by typing in your terminal:

```
$ make install
```

To run, first you need to start your virtual environment by typing:

```
$ source venv/bin/activate
```

And then you need to start pyspark on your terminal by typing:

```
$ venv/bin/pyspark
```

It will open your browse. Choose the “my_grades_notebook.ipynb” and fell free to play with it :)