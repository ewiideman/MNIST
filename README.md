# MNIST PyTorch Data Loader

A simple data loader for the MNIST dataset using PyTorch.

## Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/ewiideman/MNIST.git
    ```
2. Install the dependencies:
    ```bash
    pip install torch torchvision
    ```

## Usage

1. Import the `get_dataloader` function:
    ```python
    from dataloader import get_dataloader
    ```
2. Load the data:
    ```python
    train_loader, test_loader = get_dataloader(batch_size=64)
    ```
3. Iterate over the training data:
    ```python
    for images, labels in train_loader:
        # Your training code here
        pass
    ```

## Supported Frameworks
- [PyTorch](https://pytorch.org/)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
