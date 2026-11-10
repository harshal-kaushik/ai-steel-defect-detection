# AI Steel Defect Detection

A Jupyter notebook for classifying steel-surface defects using transfer learning with MobileNetV2 and the NEU-DET dataset.

## Notebook

The project notebook is [`neu_surface_defect.ipynb`](%20notebooks%20/neu_surface_defect.ipynb). The directory in this repository is named `notebooks ` (including a trailing space).

The notebook covers loading and inspecting the dataset, preparing image batches, training a multi-class image classifier, and reviewing training results.

## Defect classes

The six NEU-DET categories used by the notebook are:

- Cracking
- Inclusion
- Patches
- Pitted surface
- Rolled-in scale
- Scratches

## Dataset

The notebook expects the NEU-DET dataset to be available in a Kaggle-style input directory. If running outside Kaggle, update the dataset path in the notebook to match your local setup. The dataset should provide training and validation folders organized by class.

## Model and tools

- MobileNetV2 with ImageNet weights as the transfer-learning backbone
- TensorFlow / Keras for image preprocessing and model training
- Python 3 and Jupyter Notebook

## Run the notebook

Install the main dependencies in your Python environment:

```bash
pip install tensorflow numpy matplotlib
```

Then open the notebook in Jupyter and run its cells:

```bash
jupyter notebook
```

Locate `neu_surface_defect.ipynb` under the repository's `notebooks ` directory. Make sure the dataset is available at the path configured in the notebook before running the training cells.

## License

No license is specified in this repository. Contact the repository owner for permission and usage terms.
