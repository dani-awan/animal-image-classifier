# Cat, Dog and Horse Image Classifier

A CNN image classification project with a Streamlit interface.

## Features
- Upload a JPG, JPEG or PNG image.
- Predict one of three classes: cat, dog or horse.
- Display the model confidence score.

## Run locally
Use Python 3.11, then run from this project folder:

```bash
pip install -r requirements.txt
streamlit run app.py




```

## Files
- app.py: Streamlit application.
- cnn_model.keras: trained model.
- training.ipynb: original training notebook.

## Training data
The dataset is not included. Update dataset paths in the notebook before retraining.

## Limitations
Predicts one class per image: cat, dog or horse.
Does not detect multiple animals or reliably reject other image types.
Confidence scores are not calibrated probabilities.
