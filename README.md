# Deep Learning Dance — Dance-style classification (HackerEarth)

This repository contains Jupyter notebooks and dataset files for a dance-style image classification project created during a HackerEarth challenge. The notebooks demonstrate convolutional neural networks, data preprocessing and transfer learning (VGG16 / ResNet50) to classify images into Indian classical dance styles.


Quick start
-----------
1. Create a Python 3.8+ virtual environment (recommended):

```
python3 -m venv venv
source venv/bin/activate
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Open the notebooks in Jupyter / JupyterLab and run the cells. Update `data_dir` paths in the notebooks to point to your local dataset before running.

Notes
-----
- Notebooks use OpenCV, TensorFlow/Keras and scikit-learn. Training on a GPU is recommended for speed.
- Some notebooks reference `wandb` (Weights & Biases) for experiment tracking; this is optional.
- Running the notebooks will generate files such as `data.pickle` and model files (e.g. `mymodel.h5`).


Acknowledgements
-----------------
Original project / inspiration: HackerEarth challenge from which these notebooks were derived.
