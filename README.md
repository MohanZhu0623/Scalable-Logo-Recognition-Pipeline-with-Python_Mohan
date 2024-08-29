# Scalable-Logo-Recognition-Pipeline-with-Python_Mohan
Overview: This project implements a logo recognition pipeline that scans images from a specified folder and identifies logos using a pre-trained model (an existing logo recognition tool online). 
The detected logos and their confidence scores are saved into a CSV file for further analysis. This pipeline is designed to handle a large number of images efficiently, with batching support and progress visualization.

Time to Complete the Task: This task was completed in approximately 1 hour and 30 minutes.

File Formats Provided: This repository includes both .py and .ipynb files: Scalable-Logo-Recognition-Pipeline-with-Python_Mohan.py & Scalable-Logo-Recognition-Pipeline-with-Python_Mohan.ipynb: In Google Colab, you can view the steps and output. Both files contain identical code, with the .ipynb file offering a more visual and interactive experience.

Output Files: output_logo_detection_2024.csv: This CSV file includes detection results for the first 10 batches, with each batch containing 20 images, totaling 200 images. It provides details on detected logo classes and their confidence scores.

Dataset: The dataset used in this project is the FlickrLogos-27 dataset, which consists of 1,080 images containing logos from 27 different classes.  Due to the large size of the dataset, it is not included in this repository. You can download the Flickr Logos 27 dataset from [here](http://image.ntua.gr/iva/datasets/flickr_logos/).
 
Dataset Files: flickr_logos_27_dataset_images/: Contains 1,080 images. flickr_logos_27_label_map.pbtxt: Label map file mapping class IDs to logo names.

Model: The project utilizes the DeepLogo pre-trained model for logo recognition. This model is specifically trained to detect logos in images and has been fine-tuned for various logo classes. Download the model from https://github.com/satojkovic/DeepLogo?tab=readme-ov-file

 
