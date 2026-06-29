# Neural Network Trigonometric Functions

Jupyter notebook practice: approximate `sin(x)` with a feed-forward network on synthetic data from `-2π` to `2π`.

A runnable script version is in [trigonometric-functions](https://github.com/hasti1356/trigonometric-functions).

## Notebook

Open `trigonometric functions.ipynb` in Jupyter.

## Setup

Python 3.10+ recommended.

```bash
pip install -r requirements.txt
jupyter notebook
```

## Results

The notebook builds a three-layer MLP (40 → 12 → 1) and trains with Adam + MSE. The network fits the sine curve closely across the sampled range.

<!-- community contributor -->


<!-- drmikecrypto -->
