
## Files

* retinal_vessel_extraction.py : Implementation of paper's algorithm and accuracy calculation.
* additional_analysis.py : Implementation of ROC Analysis.
* Fundus Folder : Contains Subfolders- vessel (ground truth images) and imags (fundus), is a subset created from Drive Dataset

## To Run with your own dataset
* please replace the folder path and image formats for ground truth and fundus images.
* change the range in for loop to match your image's names.

## Outputs
* All images in the dataset's extracted vessels will be saved in a folder called "output_images".
* The main image, with comparison to its extracted vessels and ground truth will be stored as "Output.png" in parent folder.
* The ROC Graph will be saved as "roc.png" in the same folder.
## Installing Libraries
* !pip install opencv-python
* !pip install scikit-image
* !pip install numpy
* !pip install matplotlib
* !pip install pillow

## To run the code
* Install above given Libraries
* Directly run the retinal_vessel_extraction.py files to get extracted vessels and accuracy
* Run additional_analysis.py to get ROC Graph