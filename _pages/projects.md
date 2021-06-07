---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

* **Online Tool Condition Monitoring for Ultrasonic Welding via Sensor Fusion and Machine Learning**, [MS Thesis](https://www.ideals.illinois.edu/handle/2142/108054), [paper](https://www.sciencedirect.com/science/article/abs/pii/S1526612520308860?dgcid=coauthor)
  * The objective of MS thesis was to develop an online tool condition moitoring system for Ultrasonic Welding aiming to optimize tool life and reduce production downtime cost. 
  * The scope of work covered 
    * Installation of an automated data acquisition system using IoT sensors and NI DAQ device
    * Development of a GUI for data acquisition 
    * Design of experiments and data collection for research problem
    * Data processing, feature engineering, and feature selection
    * Machine Learning model development and hyper-parameter tuning
  * *Tools & Technologies Used*: DAQ, MATLAB, Feature Engineering, Machine Learning

* **LSTM based early diagnosis of Sepsis-3** ([github repo](https://github.com/qasimnazir/LSTM-based-Sepsis-Prediciton))
   * The gaol of final project for [CSE 6240 Big Data for Health](http://sunlab.org/teaching/cse6250/spring2021/) was to use Big Data Tools for solving a HealthCare problem.
   * Problem Formulation: Develop a machine-learning based predicitve model for early detection of Sepsis which is a medical condition where the immune system damages the body as a result of fighting infection. 
   * Methodology: 
     *  Use SQL and PySpark to caluclate features from the Medical Information Mart for Intensive Care (MIMIC)-III dataset
     *  Replicate and train a Long Short-Term Memory (LSTM) neural network model using the calculated features
     *  Experimental evaluation and parameter tuning
     *  Present findings in a report
   * *Tools & Technologies Used*: [MIMIC-III Clinical Database](https://physionet.org/content/mimiciii/1.4/), Google Big Query, SQL, PySpark, Feature Engineering, PyTorch, LSTM

* **Performacne Testing and Comparison of Object Detection implementations in MATLAB and PyTorch**
  * The objective was to profile deep neural network implementations for instance segmentation architectures both in MATLAB (Mask RCNN) and PyTorch ([detectron2](https://github.com/facebookresearch/detectron2)).
  * Developed scripts for training models in MATLAB & PyTorch with same architecture & training options and log time for various somputation steps such data loading, forward pass, backward pass, roi generation etc.
  * Compared the profiling, identiied bottelnecks and presented findings to development team for performance improvement.
  * *Tools & Technologies Used*: Computer Vision, Instance Segmentation, Mask R-CNN, detectron2, PyTorch, MATLAB, Linux, GPU 

* **Remaining Useful Life Estimation using Convolutional Neural Network**
  * The objective was to create a documnetation example that guides customers regarding employing a deep learning approach for predictive maintenance of industrial machinary. 
  * Implemented a deep learning approach for RUL estimation and compared performance with parametric models. 
  * Created a [documentation example](https://www.mathworks.com/help/predmaint/ug/remaining-useful-life-estimation-using-convolutional-neural-network.html) using MATLAB Deep Learning Toolbox and [Turbofan Engine Degradation Simulation Data Set](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan)
  * *Tools & Technologies Used*: MATLAB DeepLearning Toolbox, Predicitve Maintenance, CNN

* **Image Captioning using Convolutional Neural Networks** ([github repo](https://github.com/pulkitdixit/IE534_ConvCap))
  * The inspiration for this project was the paper - Convolutional Image Captioning by Jyoti Aneja, Aditya Deshpande and Alexander G. Schwing at the University of Illinois at Urbana-Champaign. The paper was one of the first to perform image captioning on the MSCOCO dataset using only CNNs as compared to traditional approaches that used Long Short Term Memory networks (LSTMs).
  * For our project, we implemented a similar captioning system and aimed at improving evaluation scores by using deeper encoders, and tuning for values such as epochs, number of captions per image, temperature, etc.
  * *Tools & Technologies Used*: Image Captioning, CNN, PyTorch, Linux, GPU

* **Human Activity Recognition from videos**
  * Trained deep learning models for classifying human activity from a video. 
  * Compared results from single
  video frame and multiple video frames models.
  * *Tools & Technologies Used*: Video Pre-Processing, DataLoading, CNN, PyTorch

* **Sentiment Analysis for IMDB Movie Reviews**
  * Pre-processed text data to be used by machine learning models. Implemented various techniques
  including bag of words, LSTM layers, language model and compared results.
  * *Tools & Technologies Used*: Tokenization, Word2Vec, Language Model, LSTM, PyTorch

* **Human Activities Classification from sensor signals** ([github repo](https://github.com/qasimnazir/CS-498_Applied-Machine-Learning_UIUC-Spring-2019/tree/master/HW05))
  * The project covered feature engineering from sensor signals, machine learning model development, hyperparameter tuning and model selection.
  * *Tools & Technologies Used*: Vector Quantization, Clustering, Feature Engineering, Classificaton, SkLearn

* **Africa Soil Property Prediction and Clustering** ([github repo](https://github.com/qasimnazir/ECE-CS-498_Data-Science-and-Analytics_UIUC-Spring-2019/tree/master/Projects/%5BGraduate%20Project%5D%20Africa%20Soil%20Property%20Prediction%20and%20Clustering))
  * The objective of course project was to go through all the steps in data science methodology such as problem definition, data collection, data pre-processing/cleaning, exploratory data analysis, feature engineering, model development, hyper-parameter tuning. 
  * Problem Definintion: Measuring soil properties such as Ca, P, pH, SOC using tradional laboratory based methods is expensive. We developed a regression model to predict these proprties using cheap spectroscopy data.
  * [Kaggle Challenge](https://www.kaggle.com/c/afsis-soil-properties/data), [project report](https://github.com/qasimnazir/ECE-CS-498_Data-Science-and-Analytics_UIUC-Spring-2019/blob/master/Projects/%5BGraduate%20Project%5D%20Africa%20Soil%20Property%20Prediction%20and%20Clustering/Project%20Report.pdf), [presentation](https://github.com/qasimnazir/ECE-CS-498_Data-Science-and-Analytics_UIUC-Spring-2019/blob/master/Projects/%5BGraduate%20Project%5D%20Africa%20Soil%20Property%20Prediction%20and%20Clustering/Presentation.pdf) 
  * *Tools & Technologies Used*: Regression, Clusterng, Machine Learning, PCA, Pandas, SkLearn, Ensemble

* **Accuracy-Centric Design & Fabrication of DELTA Parallel Manipulator (Undergrad Capstone Project)**
  * DELTA platform is a 3 DOF parallel robotic manipulator – a popular positioning architecture for additive manufacturing applications. 
  * This project was declared the best capstone project in the mechanical engineering department for the batch 2011-2015. 
  * The scope of project included:
    * Architecture synthesis, Forward & Inverse Kinematics, Workspace determination
    * Kinematic Error model & Optimization of Kinematic accuracy using MATLAB Optimization Toolbox
    * Multibody Dynamics – performed rigid-body & flexible-body dynamic simulations using MSC ADAMS
    * Control Systems Design – implemented a servo-motor position control model using Arduino-Mega
    * Fabrication, Integration & Testing
  * *Tools & Technologies Used*: MATLAB, Optimization, Genetic Algorithm, SolidWorks, ANSYS, MSC ADAMS, Fabrication
