
## Project Title
Disease Detection and Identification in Cotton Leaf

## Group - 23 (School of Engineering and Applied Sciences,Ahmedabad University)
- Kishan Khakhar
- Charvik Patel
- Neel Puniwala
- Jainil Vachhani
- Parth Satodiya


## Abstract
- The primary purpose of the project is to identify whether a particular cotton leaf is diseased or not and if it is
diseased, identification of the disease is done. We have considered three main diseases - Alternaria Macrospora, Bacterial Blight and Grey Mildew. We are using Multi-SVM classification algorithm, to identify among different classes. The training data
are images taken from web which are uploaded by ordinary humans. Assuming that the images are taken in uncontrolled environment, many difficulties are faced, making the machine-learning algorithm less effective. Therefore, some pre-processing like clustering, segmentation is done to improve the quality of learning. We have used various statistical features (mean,
Standard deviation, variance etc.) as training features for our algorithm.

## Introduction:
- India's is the highest producer of Cotton. Every year 20 to 25% of cotton crops fails due to disease which results into a
very huge amount of diseased crops. The common diseases observed in cottoon leafs which we have considered for our project are bacterial blight, grey mildew and alternaria macrosopra. These diseases in cotton leaf are very much prevalent in gujarat.
  
## Methodology
- Talking about the methods to detect disease and identify it :
 There are many ways to extract the diseased part from a leaf image like extracting color,shape,texture etc...
 We have used Mutli-SVM for classification of diseases and k-means clustering for image segmentation.

## Algorithm
```
1) Image Acquisition
2) Image Pre-Processing
3) Image Segmentation
4) Feature Extraction
5) Creation of Training Set
6) Training using SVM
7) Detection and Classification of test Images
```
## Video Link


## Requirements
- Matlab 
- Android Studio 3.0.0

## Output Screenshots

<img src="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Report/FinalTerm%20Report/OnlineDictionaryLearningCopy.jpg" alt="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Report/FinalTerm%20Report/OnlineDictionaryLearningCopy.jpg">

<table class="tg">
  <tr>
    <th class="tg-yw4l">Dimension(m)<br></th>
    <th class="tg-yw4l">Thresold<br></th>
    <th class="tg-yw4l">Error</th>
  </tr>
  <tr>
    <td class="tg-yw4l">50 x 50<br></td>
    <td class="tg-yw4l">175</td>
    <td class="tg-yw4l">9.89 %<br></td>
  </tr>
  <tr>
    <td class="tg-yw4l">75 x 75<br></td>
    <td class="tg-yw4l">140</td>
    <td class="tg-yw4l">9.19%<br></td>
  </tr>
  <tr>
    <td class="tg-yw4l">100 x 100<br></td>
    <td class="tg-yw4l">90</td>
    <td class="tg-yw4l">3.5%</td>
  </tr>
</table>
