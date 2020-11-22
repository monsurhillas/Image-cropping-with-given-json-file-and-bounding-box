# Image cropping with given json file and bounding box
### This repository contains the python script which has been used to crop a given dataset.
 
The Dataset Contained two types of Folders of images 
* Raw Images 
* Converted Images

Each folder contained two type of files.

* Raw Images
  * .jpg file
  * .json file
* Converted Images
  * .jpg file
  * .json file
 
 
 ### Dataset Source: https://data.mendeley.com/datasets/r43wkvdk4w/1?fbclid=IwAR3-3Sw2rmKKxWVYQQIwlA7A40db3uvCt6jyFAwakXxPonk_Rm_Qc1Xdv88
 
 Each dataset image contains a 'Bangla Language' paragraph. our goal was to extract each words from paragraph.
 the json file contained the label of each word and the bounding box points of each words. so using these value
 it was possible to crop all the words from the paragraph.
