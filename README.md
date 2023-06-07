<div align="center">

<img src="https://github.com/6tronl/artus/blob/main/docs/logo_artus.png?raw=True" height="130px">

# Tutorials to handle artus, a GeoAi python package

</div>

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7984605.svg)](https://doi.org/10.5281/zenodo.7984605)

Artus is a python package to automatically produce maps thanks to deep learning models. With artus, you can train deep learning learning models (neural network)
on raster images annotated with vector files. You can then use the trained model to predict spatial occurrences on new unlabeled rasters. Predictions can be exported to a GeoJson format and uploaded in your favourite GIS software.

Artus's documentation is available on [Read the docs](https://artus.readthedocs.io/en/latest/)

Here, we provide tutorials to get started with artus. Depending on the data you have and what you want to achieve, you may want to follow the full use cases or the step by step tutorials.

This project is being developed as part of the G2OI project, cofinanced by the European union, the Reunion region, and the French Republic.
<img src="https://github.com/6tronl/artus/blob/main/docs/logos_partenaires.png?raw=True" height="40px">

## :man_student: Quickstart
If you want to get ready with artus, you should first install it. To help you, you can follow [installation instructions](https://artus.readthedocs.io/en/latest/installation.html)!

In the case you have annotated data, whether it is georeferenced images or raster images, you may want to train a deep learning model that is able to detect specifically the classes you annotated manually. According to the type of data you have (raster images, georeferenced images) and the deep learning tasks you want to achieve, the path you will take may differ. 

### USE CASE 1 : You have tif files annotated with vector files (shapefile for example)

### USE CASE 2 : You have images with a GPS associated for all of them and you have a COCO annotation file




