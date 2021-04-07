---
permalink: /projects/
title: "Current Work"
layout: splash
header:
 overlay_image: /assets/images/coral_reef.jpg
 overlay_filter: "0.1"
 overlay_color: "#000"
---

Beginning in May 2017 I have been working on research funded by the United States Office of Naval Research (ONR) focusing on algorithms for sea floor scene understanding. Past work has focused on quantitative comparisons of superpixel segmentation (see publications page). Currently, I am focused on studying methods to align remote sensing imagery. 

# Other Research Projects
## CESU: Hurricane effects on the distribution and management of plant invasions in coastal habitats (October 2020 - Present)
- Developed approaches to measure invasive species in the Everglades using hyperspectral sensors
- Gathered field measurements using mobile spectrometers and a cablecam-mounted hyperspectral camera

# Class Projects
Outside of my main research I have completed several projects in the area of Machine Learning

## Classifying the MNIST Data
![MNIST Data](/assets/images/MNIST.png){:class="align-left"} In  this  project I  developed  a  Multilayer  Perceptron(MLP) with 100 Hidden Units to classify the MNIST Dataset. I begin by reviewing the history of Artificial Neural Networks andtheir  ability  to  solve  complex  problems.  Methods  for  applying Principal  Component  Analysis  (PCA)  and  Stochastic  Gradient Descent  with  Momentum  are  explained  to  assist  in  learning  the weights  to  classify  the  dataset.  Activation  functions  that  are compared within our study are then introduced along with theirrepresentative  equations.  Parameters  for  the  network  are  also discussed  along  with  their  intracicies.  Methods  for  parameter selection and training the network are then developed. I lastly discuss  the  results  on  the  MNIST  Dataset  based  upon  several metrics  including  percent  classification  and  cost  function  error and elaborate on the complex parameter choices and their effects on  building  a  network.  Overall,  the  results  for  each  activation function  perform  well  on  the  MNIST  test  set  with  each  having high  classification  percentages. **Read the paper** [![](/assets/images/pdflogo.png)](https://github.com/dstewart19/ProjectReports/blob/master/MultilayerPerceptronMNIST.pdf)

## Dimensionality Reduction in Hyperspectral Imagery
![HS Cube](/assets/images/hscube.jpg){:class="align-left"} In this project we compare four methods of downsampling in order to classify tree types in Hyperspectral Images (HSI). We begin by reviewing Principal Component Analysis (PCA) and compare it to another linear subspace projection - Maximimum Noise Fraction (MNF). Hierarchical clustering is also introduced as a method of combining similar features (bands). Lastly we use a simple spectral downsampling which averages small groups of bands with similar wavelengths. A support vector machine (SVM) is used to classify the reduced spectra and means and variances of classification rate are used as the main comparison metric. Overall, the results hint at the need for using around 20 bands to classify greater than 90 percent for PCA (the best of all methods). **Read the report**[![](/assets/images/pdflogo.png)](https://github.com/dstewart19/ProjectReports/blob/master/DimensionalityReductionHSI.pdf) 

## Comparing Kernel-Based Classifiers
![NL Kernel](/assets/images/nlkernel.PNG){:class="align-left"} In this project we compared three common kernel-based classifiers: support vector machine (SVM), relevance vector machine (RVM), and gaussian process regression (GPR). The results show that all three algorithms perform well and give comparable results. We noticed that RVM gives the final classification decision faster than SVM. This is consistent with previous studies. Generally, RVM and SVM both have comparable accuracy. Yet, RVM is much sparser and when the training set size grows, the number of relevance vectors increases slower than that of SVM. GPR can learn the kernel parameters automatically from data, no matter how flexible we wish to make the kernel. It can incorporate interpretable noise models and priors over functions. Moreover, it can sample from the prior to get intuitions about the model assumptions. Compared to SVMs, GPR offers several advantages: learning the kernel and regularization parameters, fully probabilistic predictions, and interpretability. **Read our report** [![](/assets/images/pdflogo.png)](https://github.com/dstewart19/ProjectReports/blob/master/ComparingKernelBasedClassifiers.pdf)

## Comparing Clustering Algorithms
![SOM Seg](/assets/images/SOMSeg.PNG){:class="align-left"} In this paper we study a variety of clustering algorithms using an RGB and a Hyperspectral dataset. We begin by introducing the clustering algorithms. Methods for applying Principal Component Analysis (PCA) are explained to assist in segmentation of the dataset. Parameters of the algorithms are also discussed along with their intricacies. Methods for parameter selection and evaluation are then developed. We lastly discuss the results on the our dataset based upon a quantitative evaluation metric known as the Object Consistency Error (OCE) and elaborate on qualitative evaluation of images without ground truth. Overall, the results show that each algorithm has a very similar mean OCE score when averaged over the RGB dataset, and they were mainly distinguished by the standard deviation of their OCE scores. **Read the paper** [![](/assets/images/pdflogo.png)](https://github.com/dstewart19/ProjectReports/blob/master/ComparingClusteringAlg.pdf)

