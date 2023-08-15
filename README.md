# Fine-tune-large-language-model
This repository contains a notebook (ESM_fine_tuning_with_aav.ipynb) that shows how to fine-tune a large language models (e.g. ESM-2) with a set of proteins/peptides interest. Note, the fine tuning was done using Transforemers (Hugging Face) with AAV protein datasets with fitness/viral assembly labelled data.

Note, the model was fine tuned with clr2 data and tested on 10,000 sequences of all_seq data (Bryan et al. 2021, doi:https://doi.org/10.1038/s41587-020-00793-4)

This notebook also demonstrates how to load a fine-tuned model and perform downstream task such as binary classification on a different dataset (e.g test set).

Required packages/libraries:
1. PyTorch
2. Hugging Face (Transformer)
3. sklearn
4. wandb
5. evaluate