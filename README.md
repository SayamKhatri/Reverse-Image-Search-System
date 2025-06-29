# Reverse Image Search System

This project demonstrates how to build a **reverse image search system** using deep learning and computer vision techniques. It allows us to upload an image and find visually similar images from a given dataset.

# What It Does

* Fine tunes VGG-16 on custom images
* Extracts image embeddings using fine-tuned CNN (VGG16).
* Computes similarity between the uploaded image and dataset images using cosine similarity.
* Returns the top most visually similar images.

# How to Use

1. **Mount Google Drive** – Stores and accesses your image dataset.
2. **Upload Dataset** – Place all searchable images in a directory on Drive.
3. **Extract Features** – CNN model generates feature vectors for all dataset images.
4. **Upload Query Image** – Upload any image you want to search similar results for.
5. **View Results** – Notebook displays the top N similar images ranked by similarity score.

# Requirements

* Python libraries: `TensorFlow`, `NumPy`, `Pandas`, `Matplotlib`, `scikit-learn`
* A folder of images on Google Drive

# Impact

* Ideal for finding duplicates, similar product listings, ranking or visual patterns.
