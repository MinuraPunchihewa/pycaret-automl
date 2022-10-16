# PyCaret AutoML

This project includes a few Python notebooks that can be used to automate various machine learning tasks through the use of `PyCaret`.

The project has been separated into folders based on the machine learning tasks that have been addressed. Each folder will consist of a notebook that can be used to automate a workflow.

For instance, by editing the `path` and `target_column` variables in the second cell of `regression/pycaret_automl_regression.ipynb`, you can run a machine learning workload on your data.

Each notebook will pick the best model for your data after comparing several options, save that model in a pickle file and even create a Dockerfile for it. The artifacts created as a result of doing so are also available within the respective folders.

## Run Locally

Clone the project,

```
https://github.com/MinuraPunchihewa/pycaret-automl.git
```

Create a Conda environment with `jupyter`, `pandas` and `PyCaret`,

```
conda create -n pycaret_automl python jupyter pandas pycaret
```

Launch Jupyter Notebook,

```
jupyter notebook
```
