# Tutorial 1: Data exploration and wrangling
Before building a machine learning model, it is important to understand and wrangle your data into an appropriate numeric format. In this tutorial, we'll look at how I like to set up my projects and some tips for exploratory visualizations.

## Part 1: Project configuration
Tutorials are not marked in this course, so it's up to you to keep track of them separately. I recommend copying the this directory to a new location rather than forking the entire `w26` repo and working out of that, otherwise you'll have a bunch of merge conflicts and extra stuff if you want to submit a PR to the main repo. Alternatively, you can create a fork and work within a separate branch.

Tools:
- [Jupyter Notebooks](https://jupyter.org/)
- [Virtual environments](https://docs.python.org/3/library/venv.html)
- [Requirements files](https://pip.pypa.io/en/stable/user_guide/#requirements-files)
- [Git](https://git-scm.com/)
- [GitHub](https://github.com)

## Part 2: Exploratory visualizations
Visualizations for the purposes of exploring data (rather than communicating results) can be "quick and dirty", but there are some guidelines to consider, as well as a few tricks that can help.

Follow along with the [notebook](exploratory_visualization.ipynb) and answer the various TODOs.

## Part 3: Reverse engineer a cleaned dataset
1. Create a new .ipynb file to explore this new dataset
2. Read the [raw data](https://archive.ics.uci.edu/dataset/222/bank+marketing) into a pandas DataFrame. You can either download the zip file, or install the `ucimlrepo` package and fetch the data directly.
3. Read the [pre-processed version](marketing_cleaned.csv) into a different pandas DataFrame.
4. Try to answer the following questions:
    1. How were the categorical features handled?
    2. Were any of the numerical categories manipulated?
    3. What additional transformations might be useful for this dataset?