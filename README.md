[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py


## Datasets

The tensor model was trained on the following four datasets:

- **Simple**
- **Diagonal**
- **Split**
- **XOR**

## Training Results

### Dataset 1: Simple

Number of Hidden layers = 3

#### Hyperparameters and Model Output

<img src="images/simple2.png" width="50%" />

#### Training Graph and Logs

<img src="images/simple3.png" width="50%" />

---

### Dataset 2: Diagonal

Number of Hidden layers = 15

#### Hyperparameters and Model Output

<img src="images/diag2.png" width="50%" />

#### Training Graph and Logs

<img src="images/diag3.png" width="50%" />

---

### Dataset 3: Split

#### Training Output Image and Graph

<img src="split/Screenshot 2024-09-26 at 6.38.02 PM.png" alt="Training Graph - Split" width="50%" />

#### Parameters

<img src="split/Screenshot 2024-09-26 at 6.51.34 PM.png" alt="Model Parameters - Split" width="50%" />

#### Training Logs

<p float="left">
  <img src="split/Screenshot 2024-09-26 at 6.39.07 PM.png" alt="Training Logs - Split - 1" width="45%" />
  <img src="split/Screenshot 2024-09-26 at 6.39.23 PM.png" alt="Training Logs - Split - 2" width="45%" />
</p>

---

### Dataset 4: XOR

#### Training Output Image and Graph

<img src="xor/Screenshot 2024-09-26 at 6.44.39 PM.png" alt="Training Graph - XOR" width="50%" />

#### Parameters

<img src="xor/Screenshot 2024-09-26 at 6.49.39 PM.png" alt="Model Parameters - XOR" width="50%" />

#### Training Logs

<p float="left">
  <img src="xor/Screenshot 2024-09-26 at 6.45.10 PM.png" alt="Training Logs - XOR - 1" width="45%" />
  <img src="xor/Screenshot 2024-09-26 at 6.45.21 PM.png" alt="Training Logs - XOR - 2" width="45%" />
</p>

---

## Conclusion

In this module, we implemented and trained a tensor model for four different datasets using MiniTorch. The results showcase the model's learning behavior on varied datasets. The training logs, final parameters, and graphs provide a clear summary of the model's performance.
