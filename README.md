# Mu-Forcing: Training Variational Recurrent Autoencoders for Text Generation

This repo contains the code and data of the following paper:
>**Mu-Forcing: Training Variational Recurrent Autoencoders for Text Generation**, ACM Transactions on Asian and Low-Resource Language Information Processing. **TALLIP** 2019

## Dependencies

- Jupyter notebook 4.4.0
- Python 3.6
- Tensorflow 1.6.0+
- Numpy

## Quick Start
Run mu_Forcing.ipynb for 
- Training: Run util.fit(train_dir='Models/') in mu_Forcing.ipynb
- Testing: Run util.test() in mu_Forcing.ipynb 
- Generating Run model.generate() in mu_Forcing.ipynb 

## Trained Model
Download the trained models (with different mu values) from the following links:
```bash
https://drive.google.com/open?id=1QW52VZaGJprERnmtSk9x5Qg0UY8LmmfR
https://drive.google.com/open?id=1PjLjG-H2NfOQQk-bdpU4aNHBFbHYYrwa
https://drive.google.com/open?id=1Z8Pzr78Dikvo97Uj93V6COC2BBUDH2wH
https://drive.google.com/drive/folders/1LkRvhh1VvVCMSG89XkspZtDYnBz9eGuN
```

## Dataset
- The APRC dataset can be found in Data/APRC
- The CMSC dataset can be found in Data/CSMC
Using pickle.load() to load the dataset (X_indices.pkl) and the vocabulary (w2id_id2w.pkl)
