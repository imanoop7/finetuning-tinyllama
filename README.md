# Finetuning TinyLlama

This repository contains the necessary files and instructions for finetuning the TinyLlama model on a custom colors dataset using the LoRA adapter.

## Overview

TinyLlama is an efficient and powerful language model that can be adapted to various tasks. In this project, we finetune TinyLlama-1.1B-Chat-v1.0 on the 'burkelibbey/colors' dataset to enhance its understanding and generation of color-related content.

## Requirements

- Python 3.8+
- PyTorch 1.8+
- Transformers 4.5+
- LoRA 

## Dataset

The dataset used for finetuning is 'burkelibbey/colors', which contains a wide range of color names and their corresponding RGB values.

## Model

The model being finetuned is 'TinyLlama/TinyLlama-1.1B-Chat-v1.0', which is a variant of the TinyLlama model specialized for chat applications.

## Finetuning Notebook

`finetuning_tinyllama.ipynb` is a Jupyter notebook that guides you through the finetuning process, including data preprocessing, model adaptation with LoRA, training, and evaluation.

## Setup

To set up your environment for finetuning, follow these steps:

1. Clone the repository:
   ``` bash
   git clone https://github.com/imanoop7/finetuning-tinyllama.git
2. Install the required dependencies:
   ``` bash
   pip install -r requirements.txt
3. Run the finetuning notebook
   
## Usage

After finetuning, you can use the model to generate color-related content or integrate it into your applications.

## Contributing

Contributions to this project are welcome! Please submit a pull request or create an issue for any enhancements, bug fixes, or feature requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to 'burkelibbey' for providing the colors dataset.
- Thanks to the TinyLlama team for developing the TinyLlama-1.1B-Chat-v1.0 model.




