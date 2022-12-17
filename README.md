# Determining the Activation of a new credit card (4IZ480)
- 4IZ480 Course Project at Faculty of Informatics and Statistics, Prague University of Economics and Business (VŠE)
- Project is conducted using Python (v 3.10.5)

## Project Structure
```
├── data                              <- Data in raw form, transformed or data from third party sources
│    │
│    ├── data_3_raw.csv               <- The original, immutable data dump
│    ├── data_pre.csv                 <- Final preprocessed data
│    ├── interim.csv                  <- Data after Optimal Binning and WoE tranformation (not included in final analysis)
│    ├── metrics.csv                  <- Evaluation metrics export for models used in this project 
│
├── models                            <- Models and objects which have been fitted within the project
│    │
│    ├── rf_model_imp.h5              <- The final optimized model trained on joined training and validation set
│
├── src                               <- Python scripts and Jupyter notebooks used in the project
│    │
│    ├── main.ipynb                   <- Final notebook
│
├── README.md                         <- The top-level README for readers of this project
├── requirements.txt                  <- requirements including necessary packages (and their versions) for project reproducibility
```

### Installing the enviroment
Before running any scripts or notebooks included in this repository, it is preferable to create a new python enviroment (using version `Python 3.10.5`), as you might encounter issues importing the required libraries.

Once you have activated your environment, navigate to the root of the project and run:
```bash
pip install -r requirements.txt
```
Upon installation you can navigate to the `src` folder and run scripts included in it.
