# Semantic Abstract Generator

This repository contains the source code for a study on generating abstracts for given texts using a fine-tuned T5-base transformer model.

## Dataset

The dataset used in this study can be found at [Dataset](https://huggingface.co/datasets/cnn_dailymail).

The subset of the dataset i used for training the model can be found at [Dataset](https://drive.google.com/file/d/15Jx_3dmQJKEcz3YB2E3WaW72_5jhoV0A/view?usp=sharing).



## Requirements

To run the code in this repository, you will need to have Python 3.6 or later installed, along with the following libraries:

- transformers
- torch
- numpy
- pandas


## Results

The model achieved a precision of 0.5, a recall of 0.6, and an f1 score of 0.6 on the test dataset.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

