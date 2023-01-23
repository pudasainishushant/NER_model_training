# Training custom NER model for resume data
## Steps to run the training
### Create a virtual environment
conda create -n spacy python==3.8.10
conda activate spacy

### Install dependencies using requirements.txt
pip install -r requirements.txt

### Run training
!spacy project run train_gpu # command to train train transformer

### Evaluate model
!spacy project run evaluate # command to evaluate on test dataset
