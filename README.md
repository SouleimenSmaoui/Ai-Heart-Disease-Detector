# AI Heart Disease Classification

A TensorFlow/Keras project that trains a binary classifier on the Cleveland heart-disease dataset.

## Project files

- `model_training.ipynb`: data exploration, model training, evaluation plots, prediction example, and a Tkinter interface.
- `Dataset/heart_cleveland_upload.csv`: dataset used by the notebook.
- `requirements.txt`: Python package dependencies.

## Run the notebook

Use Python 3.10 or 3.11, install the dependencies, and open `model_training.ipynb` from the project root so its relative dataset path resolves:

```bash
python -m pip install -r requirements.txt
jupyter notebook model_training.ipynb
```

The notebook trains a model and demonstrates predictions. Its output is for educational use only and is not intended for medical diagnosis or treatment decisions.
