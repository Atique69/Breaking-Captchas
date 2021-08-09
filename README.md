# Captcha Recognition using Optical Character Recognition 
This notebook shows my approach for recognition the captcha for computers to identify and block bots to prevent spam, DDOS, etc. It is solved regarding the CAPTCHA Images (Version 2 CAPTCHA Images) Challenge in Kaggle.

This notebook is separated into different sections, relating to the common workflow of machine learning. Hypothesis and Data collection these two things are already done. I tested different models but got various types of errors as I have not enough knowledge. I tried to find different approaches to creating models and ended up with the convolutional neural network. I am not sure about the best performance of the result. From the notebooks of Kaggle, there are many best results instead of mine. Hence I had problems with running the model and also in the use of test samples.

- ##### Setup and Check Infrastructure
- ##### Having a first look at the Data (EDA)
- ##### Data Cleaning (Feature Engineering)
- ##### Defining the architecture of our Model
- ##### Data Augmentation
- ##### Fitting data into the Model
- ##### Analyzing losses
- ##### Analyzing top six wrong identified characters
- ##### Analysis of Captcha images
- ##### Evaluation

### Approach:
------------
I started with this project by getting various libraries as I need the basic initial NumPy, pandas, seaborn, matplot to advanced ones like Keras, open cv for creating advanced models, plotting, and testing. From Kaggle, I can see different types of notebooks to get a feeling of what influences what and how does it generally works. After gaining some experience I combined several data cleaning approaches from different notebooks and general information from the internet. The most promising score yet was 0.9150743099787686.

### Evaluation:
------------
As will be mentioned in the last section, I try to compare use different models but can not find any good ones. So, here I submit the solution which I got.

### Conclusion:
------------
Overall it was an interesting project/competition which enabled me to learn new stuff and try out several tools. This is my first time I worked on image processing. It is interesting to see, that the same code giving different results when I used my pc and the pool pc of the university. I am not sure but maybe it happens because of the GPU and the Ram. I tried various preprocessing and it is quite interesting to me that the same model gives different types of accuracy. When I used test samples to find the accuracy of captcha I find difficulties and got low accuracy. I tried to solve my level best but as It was not improved so I used train samples to get my result. The convolutional neural network performed quite well in relation to the training runtime and resource consumption.

Another interesting aspect was to see the huge difference a properly cleaned dataset can make when using the same model.

### Outlook:
------------
There are several ways how to improve these scores from my point of view. Some of them I have seen in other persons works in Kaggle notebooks already.

- ##### An adaptive learning rate could also help with optimizing the results.
- ##### Run the code on GPUs and high Ram.
- ##### Using the highest level of optimization in the model.
- ##### Better segmentation of the image into character could make a good result.
- ##### Use larger grid searches to find better parameters for the given models.

### Limitations:
------------
- ##### It was not possible for me to get a good result with test sample.
- ##### It was quite slow to do some training on this model.
- ##### Some of the points mentioned in Outlook were not possible since running code in browser.

### References:
------------
Inspirations for implementation and design:

- ##### https://www.kaggle.com/vykstorm/reading-captcha-dataset-part-1
- ##### https://www.kaggle.com/vykstorm/extracting-words-from-images-with-opencv-part-2
- ##### https://www.kaggle.com/vykstorm/char-classification-using-keras-part-3
- ##### https://www.kaggle.com/varunagrawal123/captcha-final11
- ##### https://www.kaggle.com/faressayah/ocr-model-for-reading-captchas
- ##### https://www.kaggle.com/aakashnain/building-a-captcha-ocr-in-tf2-0
- ##### https://www.kaggle.com/shawon10/captcha-recognition
- ##### https://www.kaggle.com/bharatbansal/ocr-with-opencv-92-9-accuracy-on-captcha-codes
- ##### https://www.kaggle.com/fournierp/opencv-word-segmenting-on-captcha-images

Thanks to everyone whos code I have used!
