# ML2 Project

This project was made for the oral exam of the machine learning 2 module at ZHAW School of Management and Law.

It's a self build OCR-model. I tried to train a model to be able to extract the ingredients of food products.

## Motivation
I wanted to train a model that is able to read the text of the ingredients label of food products. This text could then be used for further steps in creating an app to detect food intolerances or allergies.

## Data collection
The data is from the TextOCR dataset on kaggle (https://www.kaggle.com/datasets/robikscube/textocr-text-extraction-from-images-dataset?select=annot.csv)

## Training
The model is self trained, but I was following some steps of a tutorial available at medium.com (https://medium.com/geekculture/building-a-complete-ocr-engine-from-scratch-in-python-be1fd184753b).

## Interpretation and validation
I was not able to commpare my model with a pretrained one due to the complexity of the models. I was not able to find a model that would work exactly like mine. They either could only recognize single letters or they would need an additional model. I also tried using pytesseract, but I was not able to write a functioning evaluation code snippet for that.

## Notebook
The notebook should be fully reproducable but the training needs to be run on colab pro. It uses to much memory for the free version.
The dataset will be downloaded automatically, same goes for the model, if the training isn't made.

Project by Carlo Huser (husercar@students.zhaw.ch)
