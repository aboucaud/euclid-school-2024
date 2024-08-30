# ML lectures - Rodolphe Clédassou summer school 2024

> **Marc Huertas-Company** (IAC) and **Alexandre Boucaud** (APC)  
> August 2024

## Lectures

### Cycle 1 - Thursday 29th 9:00am

- [Introduction to machine learning with (probabilistic) neural networks](https://aboucaud.github.io/slides/2024/euclid-school-ml-cycle1) - _HTML slides_

### Cycle 2 - Wednesday 28th 9:00am and Friday 30th 11:00am

- [Introduction and neural networks recap from cycle 1](https://aboucaud.github.io/slides/2024/euclid-school-ml-cycle2) - _HTML slides_
- [Convolutional neural networks, graphs, transformers and the attention mechanism](slides/cycle2_cours-compressed.pdf) - _PDF_
<!-- - [Introduction to MLOps](https://aboucaud.github.io/slides/2023/euclid-school-mlops) - _HTML slides_
-->

### Cycle 3 - Monday 26th 11:00am

- [Generative, Foundation models and Simulation-based inference (SBI)](slides/cycle3_cours-compressed.pdf)

## Notebooks

### Setup

To run the notebooks locally, install the dependencies from the `requirements.txt`
```shell
python -m pip install -r requirements.txt
```

> [!WARNING]
> macOS users with ARM processors (M1/M2/M3) please follow the instructions below to install TensorFlow (otherwise the notebook kernel will die at the beginning)
> [Apple M1/M2 specific TensorFlow installation](https://developer.apple.com/metal/tensorflow-plugin/)

### Cycle 1 - Friday 30th 2:00pm


- [Neural regression with classic and probabilistic neural networks](notebooks/cycle1_intro_nn_logprob.ipynb)  
[![][colab]](https://colab.research.google.com/github/aboucaud/euclid-school-2024/blob/main/notebooks/cycle1_intro_nn_logprob.ipynb)


- [Same notebook with MLFlow examples](notebooks/cycle1_intro_nn-mlflow-example.ipynb)  
[![][colab]](https://colab.research.google.com/github/aboucaud/euclid-school-2024/blob/main/notebooks/cycle1_intro_nn-mlflow-example.ipynb)


### Cycle 2 - Thursday 29th 2:00pm

- [Galazy zoo image classification](notebooks/cycle2-gzoo-image-classification.ipynb)  
[![][colab]](https://colab.research.google.com/github/aboucaud/euclid-school-2024/blob/main/notebooks/cycle2-gzoo-image-classification.ipynb)

- [Galazy zoo image classification - with fine tuning](notebooks/cycle2-gzoo-classification-finetuning.ipynb)  
[![][colab]](https://colab.research.google.com/github/aboucaud/euclid-school-2024/blob/main/notebooks/cycle2-gzoo-classification-finetuning.ipynb)

### Cycle 3 - Tuesday 27th 2:00pm

- [Simulation Based Inference for cosmology](notebooks/cycle3-sbi_LtU_MHo.ipynb)  
[![][colab]](https://colab.research.google.com/github/aboucaud/euclid-school-2024/blob/main/notebooks/cycle3-sbi_LtU_MHo.ipynb)

based on an example notebook by Matt Ho and additional exercices using the CAMELS public dataset (see refs).

## References

<!-- - https://arxiv.org/abs/2201.02202 -->
- [Learning the Universe Implicit Likelihood Inference pipeline - Matt Ho](https://github.com/maho3/ltu-ili)
- [CAMELS data](https://camels.readthedocs.io/en/latest/index.html)


[colab]: https://colab.research.google.com/assets/colab-badge.svg