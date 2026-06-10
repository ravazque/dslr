*This project has been created as part of the 42 curriculum by ravazque and acerezo-.*

---

## Description

DSLR (*Data Science × Logistic Regression*) rebuilds the Hogwarts Sorting Hat with machine learning: a **multiclass logistic regression classifier**, written from scratch, that assigns students to one of the four houses based on their course scores.

The project covers the full data-science workflow:

- **`describe.py`** re-implements descriptive statistics by hand (count, mean, std, min, quartiles, max) without using any library function that would compute them.
- **`histogram.py`**, **`scatter_plot.py`** and **`pair_plot.py`** visualize the dataset to find homogeneous distributions, redundant features and the most informative ones for training.
- **`logreg_train.py`** trains four one-vs-all binary classifiers with gradient descent (sigmoid + cross-entropy loss) and saves the learned weights.
- **`logreg_predict.py`** loads the weights and produces `houses.csv` with a prediction for every student.

The regression itself is implemented manually — no `sklearn` model does the work.
