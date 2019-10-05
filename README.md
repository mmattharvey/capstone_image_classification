# capstone_image_classification

General Assembly capstone project: Application of neural networks to image classification of a real-world dataset

Exploration of different modelling techniques to classify images of dogs into breeds.

Files in this repo:

project_report.html: Report write-up summarising findings

Sample files:
- sample_dog_pics: of the original 30,000+ images scraped, sample images shown here, both in original and 'cleaned' format
- dog_pic_cleaning.ipynb: code applying pre-trained neural network to categorise image content and remove non-dog image components from scraped images to arrive at 'cleaned' images
- dog_clean_pic_simple_modelling_3_breeds_1.ipynb: non-neural network modelling (e.g. logistic regression, support vector machines) on first selection of 3 breeds
- dog_clean_pic_CNN_modelling_3_breeds_1.ipynb: neural network modelling on first selection of 3 breeds
- dog_clean_pic_CNN_modelling_3_breeds_res_of_pics.ipynb: investigation into impact of changing resolution on model accuracy
- dog_pic_CNN_modelling_transfer_training.ipynb: application of ResNet50 as a feature preprocessor feeding into support vector machines classifier
