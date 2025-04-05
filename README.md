#  Taylor Series Expansion Learning with Deep Learning Models

This repository contains a comprehensive solution to three common tasks centered around **Taylor Series Expansion** using symbolic computation and deep learning techniques. All tasks are implemented in a single, clean, and well-documented Python file.

##  Overview

The objective is to generate and learn the Taylor expansions of various mathematical functions using:

-  **SymPy** for symbolic computation
-  **LSTM-based sequence learning model** (Keras/TensorFlow)
-  **Transformer-based model** (PyTorch)

---

##  Tasks Summary

###  Common Task 1: Symbolic Taylor Series Expansion
- Using `SymPy`, compute the Taylor series of:
  - `sin(x)`
  - `cos(x)`
  - `exp(x)`
  - `ln(1 + x)`
  - `tan(x)`
- Expansions are computed around `x = 0` up to 4th order (5 terms).

###  Common Task 2: LSTM Model to Learn Expansions
- Tokenize the symbolic expressions.
- Train an **LSTM** model using Keras with:
  - `Embedding Layer`
  - `Bidirectional LSTM`
  - `Dense Softmax Output`
- Evaluate **sequence-level prediction accuracy**.
- Print predicted vs. actual expressions.

###  Specific Task 3: Transformer Model to Learn Expansions
- Implement a **Transformer** using PyTorch.
  - Positional encoding is added manually.
- Trained using a `CrossEntropyLoss` (ignoring padded tokens).
- Evaluated based on **token-level accuracy**.

---
