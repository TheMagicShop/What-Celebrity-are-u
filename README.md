# What-Celebrity-are-u



**♪ Intorduction:**

* In this Notebook we will try the funny Idea of using Pattern recognition algorithms and Convolutional Neural Networks in order to predict the celebrity that's likely to be the most similar to the person in the extern uplaoded image.

* the celebrities photos are nicely captured and cropped givinig an impeccable frontal images, so make sure to upload your image under the same conditions.

* we will be using quite few Unsupervised Learning algorithms,like KMeansand Principal Component Analysis, to get into the heart of the data and extract what's suitable and what's not for our data.

* moreover, we will be trying to fit the data to a standard Deep Neural Networks models to demonstrate their failure against CNNs.

* also, we will go on a long journey in tweaking and fine tunning the hyperparameters to infer the best model.

* finally we will construct a function that helps in uploading external images and making predictions.


-- The Notebook is very detiled and have some instructive sense.

-- This Notebook uses GPU, otherwise some cells will take a huge time to run.

-- Environment: Python-Jupyter (Google Colaboratory) "GPU"

-- Frameworks: keras, scikit-learn.

The original data set contains 500 celebrities with 10 frontal and 10 profile images each, I decided to use just 80 celebrities with 10 frontal images each.

*Dataset Source: [cfpw.io](http://www.cfpw.io/)*

```
@inproceedings{cfp-paper,
  author = {S. Sengupta, J.C. Cheng, C.D. Castillo, V.M. Patel, R.  Chellappa, D.W. Jacobs},
  Booktitle = {IEEE Conference on Applications of Computer Vision},
  Title = {Frontal to Profile Face Verification in the Wild},
  Month = {February},
  Year = {2016}}
```
