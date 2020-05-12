{\rtf1\ansi\ansicpg1252\cocoartf1671\cocoasubrtf600
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Analyzing my college grades with Jupiter Notebook and PySpark\
\
The main goal of this project is to just practice a little bit of PySpark combined with Jupyter and Pandas. There\'92s nothing that much incredible here, I just read a csv file with my grades to a Spark Dataframe and use it to calculate some data. Then I plot a few graphs with Pandas. All of this running in a Jupyter Notebook.\
\
## Dependencies\
- Python 3.7+\
- Virtualenv 16.7.9+\
\
## Instalation and Execution\
\
In the main directory just run the makefile. It will create the virtual environment, install PySpark, Jupyter and Pandas.\
You can run it by typing in your terminal:\
```\
$ make install\
```\
\
To run, first you need to start your virtual environment by typing:\
\
```\
$ source venv/bin/activate\
```\
\
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0
\cf0 And then you need to start pyspark on your terminal by typing:\
\
```\
$ venv/bin/pyspark\
```\
\
It will open your browse. Choose the \'93my_grades_notebook.ipynb\'94 and fell free to play with it :)}