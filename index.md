
## Project Title
Disease Detection and Identification in Cotton Leaf

## Group - 23
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
- 


## Methodology
<img src="https://github.com//Charvik2020/Dictionary-based-filtering/raw/master/Report/Midterm%20Report/2.jpg" alt="https://github.com//Charvik2020/Dictionary-based-filtering/raw/master/Report/Midterm%20Report/2.jpg">



## Algorithm
```python
First of all we have to take n x n training image.
Create m x m blocks.
Create dictionary using blocks.
Dictionary:
	Key - Noisy image
	value - filtered image
Search algorithm
if Nearest Possible Match then
	Noisy Patch Replaced with this Image
else
	Add to Dictionary
end
return Final Filtered Image
```


## Requirements
- Python 2.7+
- PIL
- skimage
- numpy
- OpenCV

## Output
- KSVD
<img src="https://github.com//Charvik2020/Dictionary-based-filtering/raw/master/output/KSVD.jpg" alt="https://github.com//Charvik2020/Dictionary-based-filtering/raw/master/output/KSVD.jpg">

- on-line Dictionary Learning
<img src="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Report/FinalTerm%20Report/OnlineDictionaryLearning.jpg" alt="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Report/FinalTerm%20Report/OnlineDictionaryLearning.jpg">

<img src="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Report/FinalTerm%20Report/OnlineDictionaryLearningCopy.jpg" alt="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Report/FinalTerm%20Report/OnlineDictionaryLearningCopy.jpg">


- our own approach Dictionary Based Filtering
<img src="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Code%20and%20Results/Analysis/imageanalysis/output1.jpg" alt="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Code%20and%20Results/Analysis/imageanalysis/output1.jpg">

<img src="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Code%20and%20Results/Analysis/imageanalysis/output2.jpg" alt="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Code%20and%20Results/Analysis/imageanalysis/output2.jpg">

<img src="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Code%20and%20Results/Analysis/imageanalysis/Timeanalysis.jpg" alt="https://github.com/Charvik2020/Dictionary-based-filtering/raw/master/Code%20and%20Results/Analysis/imageanalysis/Timeanalysis.jpg">

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
