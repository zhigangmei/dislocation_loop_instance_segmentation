# dislocation_loop_instance_segmentation
Instance segmentation model for dislocation loops in irradiated materials

Instance segmentation models implemented in Detectron2 was used to detect the dislocation loops in irradiated additive manufactured 316 stainless steels (AM316SS). Three types of dislocation loops are considered, including edge-on-loops, inclined-loops and black-spot.

A Jupyter Notebook is included for running the trained model to detect the dislocation loops in irradiated materials. The trained model can be downloaded from the link here.

The annotation for the training and validation datasets were performed using open source code "Make Sense" and exported as the COCO style jason file. Examples of the jason files for the training and validation datasets can be found in folders train and val. 
