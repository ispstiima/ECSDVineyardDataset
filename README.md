# ECSDVineyardDataset
E-crops @ San Donaci - Vineyard Dataset (2021)

## Dataset description
This dataset is made of natural images acquired from a moving vehicle by the Intel RealSense D435 (Santa Clara, CA, USA) RGB-D camera, in a commercial field in San Donaci (Apulia, Italy). The grape variety was Vitis vinifera, cultivar “Negroamaro” (red grape variety). 

The Intel RealSense D435 produced images in portrait mode of resolution of 1280x720 pixels (see the *Images* folder). The plants were acquired frontally, at a distance between 0.8 and 1 m, as the vehicle flowed through the rows of vines. The dataset consists of 315 images captured at three stages of the seasonal grapevine phenological development:
- at fruit set (July 16th, 2021)
- before harvesting (September 10th, 2021)
- at the beginning of leaf fall (October 22nd, 2021)

These three sets of images guarantee good variability among the images of the dataset of both grape color and shape (from July to September) and leaves color (from September to October). 

Manual annotation was performed to create a segmentation ground truth of three classes (in the *Labels* folder): 
- canopy: high vegetation other than the trunk (green segments)
- grapes: grape bunches (white segments)
- background: the remaining pixels (black segments)

## Acknowledgments
This work was funded by the Project [E-crops - Technologies for Digital and Sustainable Agriculture](https://www.e-crops.it) (Italian Ministry of University and Research, PON Agrifood Program, No. ARS01_01136).

## Credits

Contact person: Annalisa Milella - [annalisa.milella@stiima.cnr.it](mailto:annalisa.milella@stiima.cnr.it)

National Research Council of Italy (CNR), Institute of Intelligent Systems and Technologies for Advanced Manufacturing (STIIMA), via Amendola 122 D/O, 70126, Bari, Italy

## Cite this dataset
-	Casado-García, A., Heras, J., Milella, A., & Marani, R. (2023). Generalization of deep learning models applied to semantic segmentation of in-field natural images in vineyards. To be presented at the European Conference on Precison Agriculture 2023 ([ECPA2023](https://www.ecpa2023.it)), Bologna, July 2-6, 2023, 

## Further references
1. Milella, A., Marani, R., Petitti, A., Reina, G. (2019) In-field high throughput grapevine phenotyping with a consumer-grade depth camera. Computers and Electronics in Agriculture, 156, 293-306.
2. Marani, R., Milella, A., Petitti, A., & Reina, G. (2021). Deep neural networks for grape bunch segmentation in natural images from a consumer-grade camera. Precision Agriculture, 22(2), 387-413.
3. Casado-García, A., Heras, J., Milella, A., & Marani, R. (2022). Semi-Supervised Deep Learning and Low-Cost Cameras for the Semantic Segmentation of Natural Images in Viticulture. Precision Agriculture 23, 2001–2026 [DOI:10.1007/s11119-022-09929-9](https://doi.org/10.1007/s11119-022-09929-9)
