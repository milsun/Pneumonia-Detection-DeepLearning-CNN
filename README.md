## Pneumonia-Detection-DeepLearning-CNN  

Detecting Pneumonia in Chest X-ray Images using Convolutional Neural Network 

### Abstract                                           

Pneumonia is an infection that inflames the air sacs in one or both lungs. The air sacs may fill with fluid or pus (purulent material), causing cough with phlegm or pus, fever, chills, and difficulty breathing. A variety of organisms, including bacteria, viruses and fungi, can cause pneumonia.


#### Dataset
<pre>
Dataset Name     : Chest X-Ray Images (Pneumonia)
Dataset Link     : <a href=https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia>Chest X-Ray Images (Pneumonia) Dataset (Kaggle)</a>
                 : <a href=https://data.mendeley.com/datasets/rscbjbr9sj/2>Chest X-Ray Images (Pneumonia) Dataset (Original Dataset)</a>
Original Paper   : <a href=https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5>Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning</a>
                   (Daniel S. Kermany, Michael Goldbaum, Wenjia Cai, M. Anthony Lewis, Huimin Xia, Kang Zhang)
                   https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5
</pre>

<pre>
<b>Dataset Details</b>
Dataset Name            : Chest X-Ray Images (Pneumonia)
Number of Class         : 2
Number/Size of Images   : Total      : 5856 (1.15 Gigabyte (GB))
                          Training   : 5216 (1.07 Gigabyte (GB))
                          Validation : 320  (42.8 Megabyte (MB))
                          Testing    : 320  (35.4 Megabyte (MB))

<b>Model Parameters</b>
Machine Learning Library: Keras
Base Model              : Custom Deep Convolutional Neural Network
Optimizers              : Adam
Loss Function           : binary_crossentropy

<b>For Custom Deep Convolutional Neural Network : </b>
<b>Training Parameters</b>
Batch Size              : 64
Number of Epochs        : 30
Training Time           : 2 Hours

<b>Output (Prediction/ Recognition / Classification Metrics)</b>
<b>Testing</b>
Precision               : 87.64%
Recall                  : 98.21%
F1-Score                : 92.62%

<!--Specificity             : -->
</pre>

##### Sample Input: 
<kbd>
<img src=https://github.com/milsun/Pneumonia-Detection-DeepLearning-CNN/blob/master/images/input.png>
</kbd>

##### Results: 
<kbd>
<img src=https://github.com/milsun/Pneumonia-Detection-DeepLearning-CNN/blob/master/images/loss.png>
</kbd>

##### Sample Output: 
<kbd>
<img src=https://github.com/milsun/Pneumonia-Detection-DeepLearning-CNN/blob/master/images/result.png>
</kbd>


##### Confusion Matrix: 
<kbd>
<img src=https://github.com/milsun/Pneumonia-Detection-DeepLearning-CNN/blob/master/images/diagnosis.png alt="Confusion Matrix" width=800px height=600px>
</kbd>

#### Tools / Libraries
<pre>
Language                : Python3
Tools/IDE               : Anaconda
Libraries               : Keras, TensorFlow
</pre>