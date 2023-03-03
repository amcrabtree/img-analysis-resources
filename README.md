# img-analysis-resources
A place to put bits and bobs related to image analysis, especially as it pertains to histopathology

## My Jupyter Notebooks

  - H&E slide analysis
  - Immunofluoresence slide analysis
  - Cell typing from immunofluorescence images

## My CLI Scripts

  - Tiling
  - Segmentation
  - Stain deconvolution
  - Slide deidentification
  - Classification using ML models

## My Walkthroughs

  - Fluorescence quantification with QuPath
  - Slide registration with Warpy using Fiji & QuPath
  - Slide annotation using QuPath
  - Using Databricks to run CLI scripts
  - Using Databricks to train an ML model

## Histology Image Open-Source Datasets

  - [Patch Camelyon (PCam)](https://github.com/basveeling/pcam): This is a dataset comprised of >300,000 tiles of 96x96 pixel size (262143 training, 32768 validation), classified as normal tissue (0) or cancerous tissue (1) within lymph nodes of patients with and without breast cancer. 
  
  - [Camelyon17](https://camelyon17.grand-challenge.org/Data/): This dataset is the more updated Camelyon dataset containing hundreds of pathologist-annotated Whole Slide Images (WSIs) from lymph nodes of patients with and without breast cancer. Each WSI's annotations are saved as an XML file containing polygon coordinates of the cancer annotation outline. Any tissue within the outlines contain cancer and any tissue outside the outlines are normal tissue. 
  
  - [The Cancer Genome Atlas (TCGA)](https://portal.gdc.cancer.gov/): This database contains thousands of WSIs from many types of cancers, along with clinical information for each patient. No pathologist annotations are available for these slides, but clinical information is often used as slide-level annotations for reference datasets within many publications. If you want to download the correct WSIs, definitely follow the walkthrough found [here](http://www.andrewjanowczyk.com/download-tcga-digital-pathology-images-ffpe/). 
  
  - [BreCaHAD](https://figshare.com/articles/dataset/BreCaHAD_A_Dataset_for_Breast_Cancer_Histopathological_Annotation_and_Diagnosis/7379186): I haven't used this one, but it's easily available and can be used to train a model for cell type segmentaiton on H&E slides. Each tissue patch has an associated point annotation file containing nuclei coordinates and corresponding cell/region class (tumor nuclei, non-tumor nuclei, mitotic cells, apoptotic cells, lumen region, and non-lumen region). 
  
