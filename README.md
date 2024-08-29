# Scalable-Logo-Recognition-Pipeline-with-Python_Mohan
Overview

This project implements a logo recognition pipeline that scans images from a specified folder and identifies logos using a pre-trained model (an existing logo recognition tool online). 
The detected logos and their confidence scores are saved into a CSV file for further analysis. This pipeline is designed to handle a large number of images efficiently, with batching support and progress visualization.

Dataset

The dataset used in this project is the FlickrLogos-27 dataset, which consists of 1,080 images containing logos from 27 different classes.  
Download the flickr logos 27 dataset from http://image.ntua.gr/iva/datasets/flickr_logos/.

Dataset Files:

flickr_logos_27_dataset_images/: Contains 1,080 images.
flickr_logos_27_dataset_distractor_set_urls: List of URLs for distractor images.
flickr_logos_27_label_map.pbtxt: Label map file mapping class IDs to logo names.

Model

The project utilizes the DeepLogo pre-trained model for logo recognition. This model is specifically trained to detect logos in images and has been fine-tuned for various logo classes.
Download the model from https://github.com/satojkovic/DeepLogo?tab=readme-ov-file

 
