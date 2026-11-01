# Machine Learning Docs

A practical, beginner-friendly documentation series for learning the Python tools and core concepts used in Machine Learning (ML) and Deep Learning (DL).

The goal is to understand **what a tool does, when to use it, how to prepare data, how to train a model, and how to save or deploy it**—not just memorize code.

## Tutorial series

| File | Topic | What you will learn |
|---|---|---|
| [`01. numpy.md`](01.%20numpy.md) | NumPy basics | Arrays, shapes, indexing, vectorized operations, and numerical operations important for ML/DL |
| [`02. pandas.md`](02.%20pandas.md) | Pandas basics | DataFrames, data cleaning, missing values, filtering, grouping, data preparation, and feature engineering |
| [`03. matplotlib.md`](03.%20matplotlib.md) | Matplotlib basics | Plotting distributions, relationships, outliers, model metrics, training curves, and confusion matrices |
| [`04. sklearn.md`](04.%20sklearn.md) | Machine Learning + Scikit-learn | Choosing traditional ML algorithms, preprocessing, pipelines, model evaluation, saving models, and deployment basics |
| [`05. pytorch.md`](05.%20pytorch.md) | Deep Learning + PyTorch | Choosing neural-network architectures, tensors, training loops, datasets, saving weights, inference, and deployment |
| [`06. tensorflow.md`](06.%20tensorflow.md) | Deep Learning + TensorFlow/Keras | Choosing architectures, Keras models, training, callbacks, saving/exporting models, and deployment options |

> **File names:** These links assume the filenames shown in the repository. Keep the filenames consistent with the links when adding or renaming files.

## Recommended learning order

1. **NumPy** — learn the array operations used throughout data science.
2. **Pandas** — load, inspect, clean, and prepare real datasets.
3. **Matplotlib** — visualize data and understand model behavior.
4. **Scikit-learn** — learn traditional ML algorithms and the complete model workflow.
5. **PyTorch** — learn neural-network fundamentals and build/train/deploy models.
6. **TensorFlow/Keras** — learn a second major DL ecosystem and its model-training/deployment workflow.

## How to study each document

- Run the code examples yourself.
- Change the example data and observe how the output changes.
- Use a small real dataset after understanding each concept.
- Keep train, validation, and test data separate when evaluating models.
- Fit data transformations on training data only, then apply the same transformations to validation, test, and production data.
- Compare a simple baseline before choosing a more complex model.
- Save both the trained model and any preprocessing steps required for inference.

## Suggested beginner project path

1. Load a CSV with Pandas and inspect missing values and data types.
2. Use Matplotlib to explore distributions and relationships.
3. Prepare features and targets, then split the data correctly.
4. Train a baseline model with Scikit-learn.
5. Evaluate errors with suitable metrics and plots.
6. Try a small PyTorch or TensorFlow/Keras model when Deep Learning is appropriate.
7. Save the model and preprocessing steps, then expose predictions through a small API.

## Important notes

- Deep Learning is not automatically better than traditional ML, especially for small tabular datasets.
- Algorithm choice depends on the task, data type, dataset size, evaluation metric, and deployment constraints.
- High training performance does not guarantee good performance on unseen data.
- Never load model or pickle-based artifacts from untrusted sources.
- Code examples are educational starting points; production applications need appropriate validation, security, monitoring, and testing.

## Useful official documentation

- [NumPy](https://numpy.org/doc/)
- [Pandas](https://pandas.pydata.org/docs/)
- [Matplotlib](https://matplotlib.org/stable/)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [PyTorch](https://pytorch.org/tutorials/)
- [TensorFlow](https://www.tensorflow.org/tutorials)

---

**Purpose of this repository:** build a clear foundation for data preparation, visualization, ML algorithm selection, Deep Learning, model evaluation, and deployment using Python.
