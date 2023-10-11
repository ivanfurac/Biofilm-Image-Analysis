# Biofilm Image Analysis
This project was done at the Faculty of Electrical Engineering and Computing, as a part of the master project course. It deals with the application of computer vision methods in biology and bioinformatics.

## Project Overview
### Introduction
This project explores quantitative methods for biofilm image analysis. Biofilms are complex communities of bacteria attached to surfaces. Those bacterial cells also produce a polymeric matrix that connects and protects them. It has been shown that the development and formation (growth) of biofilm contain phases similar to those in the development of eukaryotic organisms. When biofilm is grown in a laboratory environment, photos can be taken during the development phases. Those photos can then be used for image segmentation and further analysis. Biofilm segments can be used to obtain different measurements (e.g., determining the biofilm surface area), which show how biofilm growth works.

### Dataset
The dataset used in this project consisted of 721 biofilm photos taken every 6 minutes during biofilm growth. It was obtained from the Ruđer Bošković Institute in Zagreb.

### Tools and Methods
OpenCV is an open-source Python library that contains a large number of computer vision tools. It was used to perform biofilm image segmentation (separate biofilm from the background) and measure biofilm area and perimeter for every segment.

### Results and Future Work
The algorithms from the OpenCV library are very fast and easy to use, but they are not precise when segmenting images that show biofilm in the early stages of its development, where the biofilm itself is still not fully visible. Those early images could simply be ignored, or a more complex algorithm could be used, such as a CNN model. Another interesting task that could be considered in future work is the prediction of biofilm thickness based on pixel intensity.

## Repository and Usage
Complete code that includes image loading, preprocessing, segmentation, and quantitative analysis, together with examples of segmented images, can be found in the Jupyter Notebook `Biofilm Image Analysis - Code.ipynb` in the repository.
For Croatian readers, there is a PDF file `Biofilm Image Analysis - Project Results.pdf` that includes detailed description of the project and the project results.

The OpenCV library which is required to run the code can simply be installed using the following command:

```
pip install opencv-python
```
