# Instance segmentation of dislocation loops in AM316SS

This package is developed to perform instance segmentation of dislocation loops in additively manufactured 316 stainless steel (AM316SS). Three types of dislocation loops are considered, including edge-on-loops, inclined-loops and black-spot.

## Segmentation model

Instance segmentation model used in this package is based on the Mask-RCNN model implemented in the library [Detectron2](https://github.com/facebookresearch/detectron2).

## Installation

The environment can be installed via Anaconda: ``conda env create --file environment.yml --force``

## Run segmentation model

A Jupyter Notebook `Dislocation-loops_Detectron2_prediction_clean.ipynb` is included for running the trained model to detect the dislocation loops in irradiated materials. The trained model can be downloaded from the link here.

The annotation for the training dataset were performed using open source code "Make Sense" and exported as the COCO style Jason file. Examples of the TEM images and Jason file for the validation dataset can be found in the folder `val`. 

## Support

This material is based upon work supported by Laboratory Directed Research and Development (LDRD) funding from Argonne National Laboratory, provided by the Director, Office of Science, of the U.S. Department of Energy under Contract No. DE-AC02-06CH11357.
