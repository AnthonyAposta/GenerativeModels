# Generative Models for Meander Channel Image Generation

This project focuses on implementing Generative Adversarial Networks (GANs) and Variational Autoencoders (VAEs) to generate meander channel images. The dataset consists of 50,000 segmented meander channel images categorized into channel and non-channel regions.

## Project Structure

- The main project is located in the `ltrace_folder`.
- Place the dataset in the `ltrace/datasets/` folder.
- The `gan_models` notebook contains the models for GANs.
- The `vaes_models` notebook contains the models for VAEs.
- Trained models are stored in the `ltrace/trained_models/` folder.

## How to Build the Project

### Dependencies

- `python>=3.10`
- `poetry`

[Poetry](https://python-poetry.org/) is a modern dependency manager for Python.

### Running the Project

1. Clone this repository using Git:

```
git clone git@github.com:AnthonyAposta/GenerativeModels.git
```

2. Install dependencies using poetry:

```
poetry install
```

3. Activate the Python environment shell:

```
poetry shell
```

4. Launch JupyterLab:

```
python -m jupyterlab
```