# Deep Learning Notebooks

Three small neural network exercises in Keras / TensorFlow, written while learning the basics. Each notebook loads the data, preprocesses it, trains a small dense network, and evaluates it.

| Notebook | Task | Data | Model |
| --- | --- | --- | --- |
| `Admission-prediction.ipynb` | Regression: predict a student's chance of graduate admission from scores and profile | `Admission_data.csv` | 7 → 7 → 1 dense network (ReLU, linear output) |
| `Customer-churn-prediction.ipynb` | Binary classification: will a bank customer leave | `Churn_data.csv` | 11 → 11 → 1 dense network (sigmoid) |
| `mnist_classification.ipynb` | Multi-class classification of handwritten digits | MNIST, loaded through Keras | 128 → 32 → 10 dense network (ReLU, softmax) |

## Run them

Python 3.10 or newer.

```bash
pip install -r requirements.txt
jupyter notebook
```

The two CSV files are in the repo. MNIST downloads automatically the first time its notebook runs.
