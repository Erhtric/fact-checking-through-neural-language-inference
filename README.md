# :tv: Fact Checking through Neural Language Inference :bulb:

This repository contains the second assignment part of the **Natural Language Processing** course of the [Master's degree in Artificial Intelligence](https://corsi.unibo.it/2cycle/artificial-intelligence), University of Bologna. 

# Project Details


The main objective of such assignment is to solve a **Fact Checking** taks by using Neural Language Inference (NLI) on a pre-processed version of the [**FEVER**](https://fever.ai/dataset/fever.html) dataset using pre-trained GloVe embeddings.

We provided four different configurations and their implementation to test if any sentence embedding technique is sensibly better than another:
1. a **RNN** model where we take the last state obtained,
2. a **RNN** model where we take the mean of the states obtained,
3. a **MLP** model,
4. a **Bag of Vectors** (BoV) model.

For more details on the pipeline followed please read the report present in the report `fact_checking_nli.pdf`.

## Technologies and Frameworks

Frameworks:
- [Tensorflow (v2.3.0)](https://www.tensorflow.org/)

Platforms
- [Google Colaboratory](https://colab.research.google.com)

## Configurations and enviroments

The environment could be loaded by using `conda` by launching the command:
```shell
$ conda create --name <env> --file requirements.txt
```

## Versioning

We used Git for versioning.

# License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.