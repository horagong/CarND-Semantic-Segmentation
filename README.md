# Semantic Segmentation
## Reflection
I trained FCN-8 architecture with VGG 16 pretained on ImageNet as an encoder. I finally used 200 epochs and 0.0001 learning rate by try and error. L2 regularization showed some benefits.

Following are epochs=20, epochs=200, epochs=200 with regularization respectively.

<img src=./image/20_4_1.png width=200/>
<img src=./image/200_4_1.png width=200/>
<img src=./image/200_4_R_1.png width=200/>
<br/>

<img src=./image/20_4_2.png width=200/>
<img src=./image/200_4_2.png width=200/>
<img src=./image/200_4_R_2.png width=200/>
<br/>


<img src=./image/20_4_3.png width=200/>
<img src=./image/200_4_3.png width=200/>
<img src=./image/200_4_R_3.png width=200/>


---
### Introduction
In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Start
##### Implement
Implement the code in the `main.py` module indicated by the "TODO" comments.
The comments indicated with "OPTIONAL" tag are not required to complete.
##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

### Submission
1. Ensure you've passed all the unit tests.
2. Ensure you pass all points on [the rubric](https://review.udacity.com/#!/rubrics/989/view).
3. Submit the following in a zip file.
 - `helper.py`
 - `main.py`
 - `project_tests.py`
 - Newest inference images from `runs` folder  (**all images from the most recent run**)
 
 ## How to write a README
A well written README file can enhance your project and portfolio.  Develop your abilities to create professional README files by completing [this free course](https://www.udacity.com/course/writing-readmes--ud777).
