# DIMEE: Distributed Inference on Mobile Edge and Cloud: An Early Exit Approach

This repository is the official implementation of the work DIMEE: Distributed Inference on Mobile Edge and Cloud: An Early Exit Approach

## Requirements

We built upon our code using the [huggingface transformers](https://huggingface.co/docs/transformers/en/index). To use our code install it. 2.5.1, torch 1.4.0

## Training 

To fine-tune a pre-trained language model on and train the internal classifiers follow the command:

```setup
bash finetune_(al)bert.sh
```

## Inference

To perform inference execute the following command.

```setup
bash patience_infer_(al)bert.sh
```

## Datasets

Glue datasets are available at [GLUE datasets](https://gluebenchmark.com/)

We acknowledge [PABEE](https://github.com/JetRunner/PABEE/tree/master) authors for making their work public. 
