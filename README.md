# UHN Survival Prediction Challenge Participant #'s Code
Clone conda environment: `conda env create -f env.yml`

### Imaging Only Model
* Located at `radcurechallenge/radiomics/`
* CNN architectures are located in `radcurechallenge/radiomics/nets/default.py`

### Both Imaging + EMR Model
* Located at `radcurechallenge/dual`
* CNN architectures are located in `radcurechallenge/dual/nets/dual.py`

### How to run code
* To train models: `shell_scripts/train_[cnn/dual].py`
* To finetune a select model: `shell_scripts/finetune_[cnn/dual].py`
* To generate predictions: `shell_scripts/predict_[cnn/dual].py`