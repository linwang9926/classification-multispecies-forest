# Tree species classification in a multispecies forest using machine learning and deep learning

<p align="center">
  <img src=https://user-images.githubusercontent.com/84240210/210006248-61201630-3bc8-4f9b-887a-bab28f110bda.png width="600" />
</p>

This is a classification project ([Early Detection of Encroaching Woody Juniperus virginiana and Its Classification in Multi-Species Forest Using UAS Imagery and Semantic Segmentation Algorithms](https://www.mdpi.com/2072-4292/13/10/1975#)). 
- The **model target class name** is tree species in a multispecies forest. Four classes in total: redcedar, pine, defoliation, and others.
- The **model input** is RGB images collected by a drone.
- **Four models** in this study: *decision tree*, *random forest*, *AlexNet*, and *ResNet*.
- Original images and label can be downloaded from [Dryad dataset](https://datadryad.org/stash/dataset/doi:10.5061/dryad.9s4mw6mgh).

The picture in below is one example image with patches of the four classes in this study: (a) is an example raw image collected from the drone; (b) is a sample patch of redcedar class; (c) is a sample patch of defoliation class; (d) is a sample patch of pine class; and (e–g) are example patches of others class. Each patch was the input of the AlexNet and ResNet in this study with size of 227 × 227 × 3 or 224 × 224 × 3. The target of the models was the class for the center pixel.

<p align="center">
  <img src=https://user-images.githubusercontent.com/84240210/210007008-99337ecf-f8e8-469e-b6f3-6845ab72e179.png width="600" />
</p>

Overall performance of the four semantic segmentation algorithms on multi-species forest classification from drone images in their original spatial resolution (0.694 cm).
<p align="center">
  <img src=https://user-images.githubusercontent.com/84240210/210125244-5de22d42-7f31-4df2-8488-c8391340c15a.png width="1000" />
</p>

Visualization of examples of multi-species forest classification results with drone images in original (0.694 cm) and down-sampled spatial resolutions at 2 cm, and 5 cm. The classification performance reduced as the spatial resolution decreased.
<p align="center">
  <img src=https://user-images.githubusercontent.com/84240210/210125286-ea8e4a63-8e6b-44ea-9e89-745db98247c0.png width="600" />
</p>

Classification results of cases for small individual redcedars with the ResNet algorithm and drone images in their original (0.694 cm) and downsampled (5 cm) spatial resolution. In this study, redcedars with a diameter less than 1 m were able to be accurately classified and delineated in the images with the original resolution but failed to be detected when the spatial resolution decreased to 5 cm.
<p align="center">
  <img src=https://user-images.githubusercontent.com/84240210/210125315-dd14e938-2a2d-45e2-be7f-015e638fb44d.png width="600" />
</p>
