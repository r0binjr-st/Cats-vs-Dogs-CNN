# Cats vs Dogs CNN (PyTorch)

Simple CNN for binary image classification (cats vs dogs).

## Results

* Validation Accuracy: ~90%

## Model

* 3 Conv blocks (Conv → ReLU → MaxPool)
* Fully connected layer

## Dataset

* Kaggle Cats vs Dogs
* Loaded from Google Drive
* Classes: `Cat`, `Dog`

## Run

```bash
pip install -r requirements.txt
```

Open `cats_dogs.ipynb` in Google Colab and run all cells.

## File

* `cats_dogs.ipynb` — main notebook

## Improvements

* data augmentation
* deeper CNN
* pretrained models (ResNet, MobileNet)
