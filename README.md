# Texture Classifier Model using Flickr Material Database (FMD) Dataset

This project aims to design a texture classifier model using the Flickr Material Database (FMD) dataset. The FMD dataset was constructed with the specific purpose of capturing a range of real-world appearances of common materials, including fabric, foliage, glass, leather, metal, paper, plastic, stone, water, and wood. It consists of 100 images per category, with 50 close-up and 50 regular view images, across 10 categories.

## Dataset Description
- Dataset: [Flickr Material Database (FMD)](https://people.csail.mit.edu/celiu/CVPR2010/FMD/)
- Total Categories: 10
- Images per Category: 100 (50 close-ups and 50 regular views)
- Train-Test Split: 70% training, 30% testing

## Model Components
- **Feature Extraction**: GLCM (Gray-Level Co-occurrence Matrix) with different texture features.
- **Classifier**: KNN (K-Nearest Neighbors) classifier with k=1.

## Project Structure
- `data/`: Folder containing the FMD dataset.
- `src/`: Source code files for feature extraction and model training.
- `README.md`: Overview of the project and instructions for replicating the experiment.

## Usage
1. Download the FMD dataset from the provided link and organize it into the `data/` folder.
2. Split the dataset into training and testing sets, using 70% for training and 30% for testing.
3. Implement GLCM to extract texture features from the images.
4. Train the KNN classifier with k=1 using the extracted features.
5. Evaluate the trained model using the testing set and calculate performance metrics.

## Dependencies
- Python 3.x
- Required libraries: NumPy, OpenCV, scikit-image, scikit-learn

## Contributors
- [Ahmed Mohamed Fathy](https://github.com/amfathy)
