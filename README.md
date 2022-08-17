# Investigating TMDb movie data (cleaned from original data on [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata))

## Introduction
What can we say about the success of a movie before it is released? Are there certain companies that have found the consistent formula? Given the major films costing over $100 million to produce can still flop, this question is more important than ever to the industry. Film aficionados might have different interests. Can we predict which films will be highly rated, whether or not they are a commercial success?[^1].

## Dataset
In this project, I worked on the following dataset:
- __tmdb-movies__: This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. These movies were released between the period of 1960 - 2015.

## Summary of Findings
Over the years the Drama genre has maintained a steady growth. It held the top spot as the genre with the most numbers of movies from the 1960s to the 1980s and only dropped briefly to second place in the early 1990's when the Action genre had an uptick in numbers of movies released but it then regained the top spot in the late 1990s and has experienced exponential growth ever since. The Horror genre is the least popular genre from year to year.

The lack of sufficient data in the budget hindered my conclusion on the features of popular movies.

## Key Insights for Presentation
You can see content on nbviewer: [Jupyter Notebook]()

OR download the HTML file in the subdirectory to view the content in the browser on your computer at anytime offline.

## Getting Started
> These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- You need to be able to work in a Jupyter Notebook on your computer
- You need an installation of Python and the following libraries need to be installed. (You can install these packages via conda or pip)
  * pandas
	* NumPy
	* Matplotlib
	* Seaborn

### Installing
These examples tell you how to get a development environment running

I recommend installing Anaconda, which comes with all of the necessary packages, as well as Jupyter Notebook. Here are the installation steps:

- Download the [installer]( https://www.anaconda.com/download/). Choose the Python 3.6 or higher version, and the appropriate 64/32-bit installer.
- Refer to the installation instructions [here](https://docs.anaconda.com/anaconda/install/).
- Verify the installation, as mentioned [here](https://docs.anaconda.com/anaconda/install/verify-install/)

If you already have Anaconda installed, use the `environment.yaml` to create the exact environment I used during the project by typing the line below into the Anaconda terminal in the same folder where the environment file is saved on your computer

```
conda env create -f environment.yaml
```
OR If you're not using Conda, you can use pip to install dependencies with the `requirements.txt` file by typing this line into your terminal

```
pip install -r requirements.txt
```

## Built With
- [Anaconda](https://www.anaconda.com) - Dependency Management
- [Jupyter Notebook](https://jupyter.org/) - Data analysis documentation

## Authors
- Gilbert Adikankwu

## License
This project is licensed under the GNU License - see the [LICENSE](https://github.com/10xDatabro/Dataset-investigation/blob/main/LICENSE)

## Acknowledgments
- Udacity ALX-T Data Analyst Nanodegree
