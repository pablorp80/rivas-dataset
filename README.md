[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

# Rivas Dataset

## Description
This dataset consists of hand gestures of the numbers 0 to 9 in sign language. We used depth imagery followed by automatic segmentation of the hand region.  For full details of the algorithm read my thesis:
-- aqui van datos para descargar tu tesis, si es que la van a publicar en linea.

## Citation
We request you cite the following thesis work if you use our data:
-- aqui van los datos de la tesis, tu nombre, institution etc.

## Downloading the data
Download the file `S01.tar.gz`

Unpack the gzip file as follows:
`tar xvf S01.tar.gz`

The data should be in a folder named `S01`. It contains images with the following naming format `S01_CXX_YYY.png` where `XX` denotes the class identifier: ten digits = ten classes, from `01` to `10`. And `YYY` is a consecutive number from `0` to `299` indicating that there are 300 different images per class. For example, an image called `S01_C03_123.png` indicates that it is of the third class and it was given a consecutive number of 123. 

## License
[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/)
