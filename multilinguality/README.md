
# Multilinguality

## Installation

You need to install

    1. transformers
    2. datasets
    3. sentencepiece

## Data files
All the datasets are added in the data folder. While running the code change the file path accordingly.

## Run the code
There are two files for easyMix.ipynb and baseline.ipynb to generate results for easymix and bert baseline models respectively.
If you want to run the baselines change the base_model, lang and model_choice variable. For example,
if you want to run code for French data on xlm-r model then change:
base_model = 'xlm-roberta-base'
lang = 'french'
model_choice = 3 ###select index from the model list

To run the EasyMix, change only lang variable to run on the corresponding language data.
