DATASET DESCRIPTION
=======================


This dataset contains 32 groundtruths for images from the MESSIDOR dataset. The images are not included in the dataset and need to be downloaded from the MESSIDOR dataset: http://www.adcis.net/en/Download-Third-Party/Messidor.html

The image list can be found in 'grades.xlsx'

This is an explanation of the folders in the database:

* groundtruth/OD

 Contains all the optic disc masks for all the images

* groundtruth/MA

> Contains the microaneurysm groundtruths for all the images. The `images/` folder contains the MA binary mask groundtruths. These are subdivided into folders that respresent the categories (refer to the dataset description for more details). The 'markers/' folder contains the MA groundtruth .mat files generated using the [`imannotate`](https://github.com/motatoes/imannotate.m) software. In addition, this folder also contains a `csv/` folder that contains csv files for each of the 32 images. These CSV files present information about the position (x,y) and radius of each MA candidate in the groundtruth. Note that we follow the convention that the origin of the axis is in the top-left corner of the image and the x-axis increases horizontally to the right while the y-axis increases vertically as you go down.

* groundtruth/FOV/

> Contains all the field of view masks for all the images (binary masks)

DOWNLOAD
=============

To download the dataset, go to the [releases page](https://github.com/motatoes/messidor-groundtruth/releases). It would be appreciated if you could [fill this form](https://docs.google.com/forms/d/e/1FAIpQLSdNU7sSRR54C2AKJUnitRaNilYbLbX_EZG9TCFXpABq0XOeuQ/viewform) if you are using this dataset for academic purposes.
