# Tree species classification in a multispecies forest
<img src=https://user-images.githubusercontent.com/84240210/210006248-61201630-3bc8-4f9b-887a-bab28f110bda.png width="500" />

This is a classification project ([Early Detection of Encroaching Woody Juniperus virginiana and Its Classification in Multi-Species Forest Using UAS Imagery and Semantic Segmentation Algorithms](https://www.mdpi.com/2072-4292/13/10/1975#)). 
- The target class name is tree species in a multispecies forest. Four classes in total: redcedar, pine, defoliation, and others.
- The input is RGB images collected by a drone.

The picture in below is one example image with patches of the four classes in this study: (a) is an example raw image collected from the drone; (b) is a sample patch of redcedar class; (c) is a sample patch of defoliation class; (d) is a sample patch of pine class; and (e–g) are example patches of others class. Each patch was the input of the AlexNet and ResNet in this study with size of 227 × 227 × 3 or 224 × 224 × 3. The target of the models was the class for the center pixel.
![image](https://user-images.githubusercontent.com/84240210/210007008-99337ecf-f8e8-469e-b6f3-6845ab72e179.png)
