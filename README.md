[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Rye](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/rye/main/artwork/badge.json)](https://rye.astral.sh)

# Neural Network Playground
Basic implementations of neural network models using Jax and Pytorch.

## Development Environment

- common
    ```
    Ubuntu 20.04
    Python 3.12.3
    Cuda 12.1
    ```
- [jax](https://jax.readthedocs.io/en/latest/index.html)
    ```
    Jax 0.4.35
    Flax 0.10.2
    Optax 0.2.4
    ```
- [pytorch](https://pytorch.org/)
    ```
    Pytorch 2.3.1
    ```

## Setup

### For Jax Users
```bash
git clone https://github.com/MizuhoAOKI/neural_network.git
cd neural_network
cp ./pyproject_jax.toml ./pyproject.toml
rye sync
```

### For Pytorch Users
```bash
git clone https://github.com/MizuhoAOKI/neural_network.git
cd neural_network
cp ./pyproject_pytorch.toml ./pyproject.toml
rye sync
```

## Usage

### For Jax Users
```bash
rye run jupyter notebook notebooks/mlp_jax.ipynb
```

### For Pytorch Users
```bash
rye run jupyter notebook notebooks/mlp_pytorch.ipynb
```

<img src="./media/mlp.png" width="500" />