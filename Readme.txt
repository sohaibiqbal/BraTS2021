Brain Tumor Segmentation and MGMT Status Classification Pipeline
This repository contains the implementation of a pipeline for brain tumor segmentation and MGMT status classification using deep learning models. The pipeline utilizes multimodal MRI data and incorporates a 3D Residual U-Net for segmentation and a 3D ResNet10 for classification.

Files
segmentation.ipynb: Jupyter Notebook file containing the code for the segmentation phase of the pipeline.
classification.ipynb: Jupyter Notebook file containing the code for the classification phase of the pipeline.
Usage
Clone the repository:
bash
Copy code
cd brain-tumor-pipeline
Set up the environment:
Install the required dependencies specified in the notebook files.
Make sure you have Jupyter Notebook installed.
Prepare the dataset:

Download the BraTS2021 dataset from http://braintumorsegmentation.org/ and preprocess the MRI scans.
Run the notebooks:

Open segmentation.ipynb and classification.ipynb in Jupyter Notebook.
Configure the necessary parameters within the notebooks.
Execute the cells to run the segmentation and classification phases.
Evaluate the results:

Assess the segmentation and classification performance within the notebooks.
Visualize the segmentation masks and classification predictions.
