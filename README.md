# Spartificial Solar Flares Prediction

This project was created as a part of research internship at Spartificial

## Run Locally

Clone the project

```bash
  git clone https://github.com/dheer309/spartificial-solar-flare-prediction.git
```

### Jupyter notebook

If you are running this project on a jupyter notebook, start the jupyter notebook by typing `jupyter notebook` on the terminal or cmd (assuming you have jupyter/anaconda installed), then go to the project directory

```bash
  cd spartificial-solar-flare-prediction
```

Then, comment the lines which have pd.read_csv and replace them with the comments below, which are the lines that work for jupyter notebooks

If you are facing errors like package not found in jupyter notebook, then create a new cell, run the code given below, then rerun the jupyter notebook.

```
# Install a pip package in the current Jupyter kernel
import sys
!{sys.executable} -m pip install numpy # replace numpy with your own package name
```

### Google Colab

If you're running this project on Google Colab, then upload the dataset to your google drive before running the project
