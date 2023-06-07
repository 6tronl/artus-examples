<div align="center">

<img src="https://github.com/6tronl/artus/blob/main/docs/logo_artus.png?raw=True" height="130px">

# Predict geospatial data with artificial intelligence

</div>

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7984605.svg)](https://doi.org/10.5281/zenodo.7984605)

Artus is a python package to automatically produce maps thanks to deep learning models. With artus, you can train deep learning learning models (neural network)
on raster images annotated with vector files. You can then use the trained model to predict spatial occurrences on new unlabeled rasters. Predictions can be exported to a GeoJson format and uploaded in your favourite GIS software.

To handle large raster file, artus provides a way to tile raster into smaller tiles according to different cutting grids.

Artus has already been implemented in three use cases using 3 differents inputs data : satellite images to detect gillnets vessels, orthomosaics to detect corals
species and under water images marked with a georeferenced point to detect marine species. 

Artus's documentation is available on [Read the docs](https://artus.readthedocs.io/en/latest/)

This project is being developed as part of the G2OI project, cofinanced by the European union, the Reunion region, and the French Republic.
<img src="https://github.com/6tronl/artus/blob/main/docs/logos_partenaires.png?raw=True" height="40px">

## :man_student: Quickstart
If you want to get ready with artus, you should first install it. To help you, you can follow [installation instructions](https://artus.readthedocs.io/en/latest/installation.html)!

In the case you have annotated data, whether it is georeferenced images or raster images, you may want to train a deep learning model that is able to detect specifically the classes you annotated manually. According to the type of data you have (raster images, georeferenced images) and the deep learning tasks you want to achieve, the path you will take may differ. 

### USE CASE 1 : You have tif files annotated with vector files (shapefile for example)

### USE CASE 2 : You have images with a GPS associated for all of them and you have a COCO annotation file




