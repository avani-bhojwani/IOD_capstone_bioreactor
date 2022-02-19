           

# Prediction of Cell Growth in Bioreactors

This capstone project was completed as part of Institute of Data’s Data Science and Artificial Intelligence course.

Scientists have been exploring whether cardiomyocytes (i.e. heart muscle cells) can be transplanted into patients to support recovery after heart attacks. Stem cells can be converted into cardiomyocytes in a bioreactor over a 10-day process. This project aims to predict the outcome of this process using data up to day 7. If a machine learning model can predict which experiments will produce an insufficient percentage of cardiomyocytes, then these experiments can be terminated, thereby saving time and cost of operating and monitoring bioreactors.

**Data source:**

Williams, Bianca, et al. "Prediction of human induced pluripotent stem cell cardiac differentiation outcome by multifactorial process modeling." Frontiers in bioengineering and biotechnology 8 (2020): 851. https://www.frontiersin.org/articles/10.3389/fbioe.2020.00851/full#B10

**You can view notebooks from this project in this order:**

1_EDA.ipynb (exploratory data analysis)

2_comparing_models.ipynb

3_model_pipeline.ipynb

## To view this project in Google Colaboratory, click [here](https://colab.research.google.com/github/avani-bhojwani/IOD_capstone_bioreactor/blob/master)

Alternatively, follow the instructions below to install this project to your local machine.

## Installation Instructions

You will need to have installed [Anaconda](https://www.anaconda.com/distribution/), [git](https://git-scm.com/), and [Jupyter notebook](https://test-jupyter.readthedocs.io/en/latest/install.html).

Run the following commands in a terminal.

Clone the repository:

```$ git clone https://github.com/avani-bhojwani/IOD_capstone_bioreactor.git
$ cd IOD_capstone_bioreactor_cell_growth```

Create a conda environment from the environment.yml file:

`$ conda env create -f environment.yml`

Activate the new environment:

`$ conda activate bioreactor`

Finally, launch Jupyter notebook!

`$ jupyter notebook`
