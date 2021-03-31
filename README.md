# RemoteSensing-Classification-practice
The remote sensing image classsification of Potsdam dataset using CNN(tensorflow)

### 2D Semantic Labeling Contest - Potsdam
https://www2.isprs.org/commissions/comm2/wg4/benchmark/2d-sem-label-potsdam/

### Data description
The data set contains 38 patches (of the same size), each consisting of a true orthophoto (TOP) extracted from a larger TOP mosaic, see Figure below and a DSM. 

![image](https://user-images.githubusercontent.com/66828546/113218845-82088e00-9280-11eb-9cd5-a42a96eea2d0.png)

Outlines of all patches given in Tab.1 overlaid with the true orthophoto mosaic. Numbers refer to the individual patch numbers, encoded in the filenames as well
The ground sampling distance of both, the TOP and the DSM, is 5 cm. The DSM was generated via dense image matching with Trimble INPHO 5.6 software and Trimble INPHO OrthoVista was used to generate the TOP mosaic. In order to avoid areas without data (“holes”) in the TOP and the DSM, the patches were selected from the central part of the TOP mosaic and none at the boundaries. Remaining (very small) holes in the TOP and the DSM were interpolated.
The TOP come as TIFF files in different channel composistions, where each channel has a spectral resolution of 8bit:

IRRG: 3 channels (IR-R-G)
RGB: 3 channels (R-G-B)
RGBIR: 4 channels (R-G-B-IR)

### Some prediction on test tile...
![prediction](https://user-images.githubusercontent.com/66828546/113218568-0b6b9080-9280-11eb-9eb5-bb709ac6bc48.jpg)

