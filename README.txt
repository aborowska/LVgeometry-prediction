EXPORT_CROPS.py takes raw data and prepares for segmentation.

EXPORT_SEG.py loads data created in EXPORT_CROPS and calls exportSEGsoftware.py which runs the segmentation software.

EXPORT_3DMESH.py uses network to create the reconstruction of the LV geometry.

dataset contains all of the images to be used for segmentation.