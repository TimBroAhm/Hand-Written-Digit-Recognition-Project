# Handwritten Digit Recognition

A deep learning project that recognizes handwritten digits (0–9) from images using a neural network in Python. It is a classic image classification task and a practical introduction to computer vision and model evaluation.

## Repository Contents

| File | Description |
|------|-------------|
| `Handwritten_Digit_Recognition.ipynb` | Main notebook: data loading, preprocessing, model training, and evaluation |
| `codereview.py`, `finalcr.py`, `new.py`, `reject.py` | Python scripts used to test automated code review on this repository |
| `.github/workflows/` | GitHub Actions workflow configuration |

## Project Workflow

1. **Data loading:** load a dataset of labeled handwritten digit images.
2. **Preprocessing:** normalize pixel values and reshape the images for the model.
3. **Model training:** train a neural network to classify digits from 0 to 9.
4. **Evaluation:** measure accuracy on unseen test images.
5. **Prediction:** classify new handwritten digit images.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/TimBroAhm/Hand-Written-Digit-Recognition-Project.git
cd Hand-Written-Digit-Recognition-Project
```

2. Open `Handwritten_Digit_Recognition.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
3. Run the cells in order. The required libraries are imported at the top of the notebook.

## Tech Stack

Python · Deep Learning · Jupyter · GitHub Actions

## Future Work

- Experiment with deeper convolutional architectures
- Add data augmentation to improve robustness to different handwriting styles
- Build a small web app for drawing and recognizing digits in the browser

## Author

**Tim** ([@TimBroAhm](https://github.com/TimBroAhm))
