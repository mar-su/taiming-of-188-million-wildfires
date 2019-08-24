# Taming Of 1.88 Million Wildfires
Analysis of 1.88 Million US Wildfires-dataset on kaggle.

Following questions are analyzed:
1. Which state is the moste fire prone?
2. How does the evolution look like and is there a trend? 
3. Are there seasonal fluctuations? / Wildfires have to occure much more often in summer, haven't they?
4. Can we predict the size / area of a fire?

# Getting started
Set up the environment with [Anaconda](anaconda.org):
```
conda env create --file environment.yml
```
Once this is done, you can start your environment with:
```
conda activate wildfires
```
And start `jupyter` with `jupyter notebook`.

Download the SQLite-database `FPA_FOD_20170508.sqlite` from the kaggle-repository [here](https://www.kaggle.com/rtatman/188-million-us-wildfires).

# Structure
You can find two notebooks in this project. The file `Taming Of 1.88 Million Wildfires.ipynb` will provide concise answers to the questions above, while the file `EDA.ipynb` provides additional insights and can be seen as home for experiments.

**Have fun!**
