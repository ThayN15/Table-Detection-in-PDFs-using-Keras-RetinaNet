# Table-Detection-in-PDFs-using-Keras-RetinaNet

This project is to detect tables in pdf documents using Keras-RetinaNet. 
- Dataset of 1270 images was created  by obtaining pages from annual reports of companies (PDF Documents) and as well as from a publicly available Marmot Table Dataset https://www.icst.pku.edu.cn/cpdp/sjzy/. 
- These pages were then converted to images and on these images, tables were annotated using the tool labelImg. https://github.com/tzutalin/labelImg. 
- The code for the implementation of this project was obtained from PDFTableExtract project by ferrygun https://github.com/ferrygun/PDFTableExtract.

This repository includes a sample of Images and Annotations that were used in this project. 


Below is one of the predicted image obtained from the trained model. 

![SDB-page41](https://user-images.githubusercontent.com/53529711/131242386-ce374e97-73ce-4f01-b2ff-7e3573ac0f80.jpg)




Reference
- Djaja F. (2020). PDF Table Extraction with Keras-RetinaNet. Retrieved from: https://djajafer.medium.com/pdf-table-extraction-with-keras-retinanet-173a13371e89
