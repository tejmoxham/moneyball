# MoneyBall Project

A project performed in collaboration with Vela Partners which evaluates the likelihood of start up success using information about the founders background and investor metrics. Features where generated using the MoneyBall and Midas Touch dataset and used as the input for classification models which predict the true success ratio better than random chance.

## Installation
A python version later than 3.7 is required, the python libraries that the notebooks depend on are listed in the `requirements.txt` and can be install by running,
```
pip install -r requirements.txt
```
It is recommended that a new separate conda environment is generated and used for the project which can be achieved using the `conda create` command. 

## Usage
The project is divided into three jupyter noteboooks which can be run separately provided processed datasets are available in the `/data/moneyball_processed/`
 - Prepare & Feature Engineering: Used for importing, combing and tidying up the datasets, then generating features of interest. 
 - Initial Statistical Data Analysis: Visualisation of the initial feature correlations with startup success and which to choose for our final model.
 - Machine Learning Models: Training and testing of models using k-folds with various classifiers and evaluation using precision-recall ratio curves.
 
 ## References 
[Midas Touch](https://github.com/velapartners/midas_touch_v1)
A project which used a graph ranking algorithm to generate normalized investor scores based on a set of "brand name" investors.

[MoneyBall](https://github.com/velapartners/moneyball-v2)
A previous interns results on the same MoneyBall dataset similarly using the founders background and investor information.

