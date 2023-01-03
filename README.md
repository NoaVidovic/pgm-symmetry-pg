# pgm-symmetry-pg

## Installation
To run this code on your device, use `git clone` to download the code and within the downloaded directory run
```
conda env create -n venv-pg -f environment.yml
```
This will create a virtual Python environment with all the required packages. You can then use `conda activate venv` to
activate the virtual environment and run the scripts in this repository. To open and run the .ipynb notebooks in this
repository, use `jupyter notebook`.

## MongoDB Database Restoration
Assuming you already have the MongoDB CLI utilities installed and configured, to restore the database containing all
the data used in this project, use `mongorestore dump/ --gzip` within the cloned repository.
