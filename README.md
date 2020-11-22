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
 
 ## Input image of the Raw file:
 ![raw img input](https://github.com/monsurhillas007/Image-cropping-with-given-json-file-and-bounding-box/blob/main/Sample%20Media/RawImgwithoutcrop/0_21_0.jpg)
 
 
 ## Input image of the Converted file:
 
![converted img input](https://github.com/monsurhillas007/Image-cropping-with-given-json-file-and-bounding-box/blob/main/Sample%20Media/ConvertedImgwithoutcrop/0_21_0.jpg)
 
 ## Output image of the Raw File(Cropped):
 ![crop raw one](https://github.com/monsurhillas007/Image-cropping-with-given-json-file-and-bounding-box/blob/main/Sample%20Media/rawimgwithcrop/%E0%A6%85%E0%A6%B0%E0%A7%8D%E0%A6%A5%E0%A7%87.jpg)
 
 ![crop raw two](https://github.com/monsurhillas007/Image-cropping-with-given-json-file-and-bounding-box/blob/main/Sample%20Media/rawimgwithcrop/%E0%A6%85%E0%A6%B0%E0%A7%8D%E0%A6%A5%E0%A7%87%E0%A6%B0.jpg)
 
 ![crop raw three](https://github.com/monsurhillas007/Image-cropping-with-given-json-file-and-bounding-box/blob/main/Sample%20Media/rawimgwithcrop/%E0%A6%85%E0%A6%B2%E0%A6%B8.jpg)
 
 ## Output image of the Converted file(Cropped):
  ![crop raw one](https://github.com/monsurhillas007/Image-cropping-with-given-json-file-and-bounding-box/blob/main/Sample%20Media/covertedimgwithcrop/%E0%A6%85%E0%A6%B0%E0%A7%8D%E0%A6%A5%E0%A7%87.jpg)
 
 ![crop raw two](https://github.com/monsurhillas007/Image-cropping-with-given-json-file-and-bounding-box/blob/main/Sample%20Media/covertedimgwithcrop/%E0%A6%85%E0%A6%B0%E0%A7%8D%E0%A6%A5%E0%A7%87%E0%A6%B0.jpg)
 
 ![crop raw three](https://github.com/monsurhillas007/Image-cropping-with-given-json-file-and-bounding-box/blob/main/Sample%20Media/covertedimgwithcrop/%E0%A6%85%E0%A6%B2%E0%A6%B8.jpg)
