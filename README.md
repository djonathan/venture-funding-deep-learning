# venture-funding-deep-learning
Apply Deep Learning models to predict success among venture funding applicants.

---
## Technologies

Python modules used:

* pandas
* pathlib
* tensorflow
* tensorflow.keras.layers
* tensorflow.keras.models
* sklearn.model_selection
* sklearn.preprocessing
---
## In a Jupyter Notebook:
* Prepare the data for use on a neural network model.
* Compile and evaluate a binary classification model using a neural network.
* Optimize the neural network model.

---

## Summary
The number of epochs (50) was kept constant across all models.  

The original 2-layer model with 116 input features yielded an accuracy score of 0.7285.

A second model dropped several of the categorical features, resulting in a lower accuracy of 0.7017.

A third model returned to the original feature-set, but increased the number of neurons by a factor of 2, resulting in an accuracy of 0.7300, not significantly different from the original.

---

## Contributors

[David Jonathan](https://www.linkedin.com/in/david-jonathan-1b9470/)

---

## License

Licensed under the [MIT License](https://github.com/tmbo/questionary/blob/master/LICENSE). Copyright 2021 David Jonathan