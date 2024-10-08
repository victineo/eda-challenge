# eda-challenge
This is a basic practical challenge about **Exploratory Data Analysis** with Python.

## Tasks
Analyze a database and, based on it, extract:
* Available data types
* Period of the analysis
* Database size
* Check for null values
* Outliers

## Database to be used
You can access the CSV file used as database in the **develop** branch.

## Dependencies
### pipenv
pipenv is a dependency management tool for Python that allows creating and managing isolated virtual environments for projects, ensuring that dependencies are consistent and easy to manage.

To install pipenv, run:
```
$ pip install --user pipenv
```

Then, to install pipenv on your project directory, run:
```
$ pipenv install
```

And finally, to activate your new virtual environment, run:
```
$ pipenv shell
```

Learn more about [pipenv](https://pipenv.pypa.io/en/latest/index.html).

---

To install any of the following dependencies on your project **virtual environment**, run:
```
$ pipenv install <name>
```
and replace `<name>` with the correct dependecy name.

If you're not using pipenv or any kind of virtual environment, do the same thing, but with:
```
$ pip install <name>
```

### ipykernel
ipykernel is a kernel for Jupyter Notebook that allows running Python code in an interactive environment, providing features such as autocomplete, debugging, and result visualization.

Learn more about [ipykernel](https://pypi.org/project/ipykernel/).

### numpy
NumPy is a library for numerical computing in Python, providing support for multi-dimensional arrays and matrices, as well as a variety of functions for mathematical and statistical operations. It is fundamental for data analysis and is often used in conjunction with other libraries such as Pandas and Matplotlib.

Learn more about [numpy](https://numpy.org/).

### pandas
pandas is an open-source library for data manipulation and analysis in Python, providing data structures and operations to work with structured data, including data import/export, merge, groupby, pivot, reshape, and more.

Learn more about [pandas](https://pandas.pydata.org/).

### matplotlib
matplotlib is an open-source library for creating graphs and visualizations in Python, allowing the creation of a variety of charts, including lines, bars, scatter, histograms, and more.

Learn more about [matplotlib](https://matplotlib.org/).