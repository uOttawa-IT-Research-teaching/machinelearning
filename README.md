# Machine Learning Series

Welcome to the Bilingual (French and English) Machine Learning Training Series hosted by uOttawa IT Research and Teaching!

## Collaborators

The production of the Machine Learning Series represents a significant bilingual endeavor aimed at enhancing awareness, understanding, and utilization of Artificial Intelligence (AI) and Machine Learning (ML) within the research community.

The development of Machine Learning Series Training involved a collaborative effort from a team consisting of scientific computing specialists, a specialist from the Data Literacy Research Institute focusing on Research Data Management, advisors, and research assistants. Led by a diverse team with expertise spanning scientific computing, AI training, and research data management the initiative seeks to integrate best practices in research data management with AI and ML tutorials. With an advisor from the University of Ottawa’s research support and infrastructure team, the project ensures alignment with academic standards and aims to empower researchers and support staff with easily accessible, reusable training assets in both French and English.

We use the credit taxonomy to acknowledge authorship roles. The participants agreed to be credited for their contributions during the collaborative document creation process and were reminded of their role as authors prior to the document's publication.

Project lead: Jarno van der Kolk, PhD, Senior Scientific Computing Specialist (University of Ottawa)

AI training expert: Peter Darveau P. Eng. CED - Scientific Computing Support / Developer (University of Ottawa)

RDM expert: Felicity Tayler, MLIS, PhD, Outreach Director \| DLRI and Research Data Management Librarian (University of Ottawa)

Advisor: Julie St-Pierre, Associate Vice-President, Research Support and Infrastructure

## Target Audience:
This training series is tailored for:

* Researchers, scientists, and data practitioners involved in data-intensive research projects.
* Graduate students and academics seeking to enhance their data management and analysis skills.
* Professionals interested in leveraging machine learning techniques for research data analysis and discovery.

## How Does This Learning Resource Work?
This training series aims to address three key gaps in understanding AI and machine learning (ML) methodologies: providing an introduction to AI and ML models, preparing data for these models, and incorporating research data management (RDM) practices into AI and ML-enabled methodologies. While AI and ML are recognized for their potential to automate tasks, identify patterns in data, and assist with analysis, many researchers struggle to apply these computational methods effectively to their research due to several challenges. These include the complexity of selecting the appropriate model for their data, the common omission of data cleaning processes in tutorials, resulting in mismatches between learned models and real-world data, and the separation of AI and ML techniques from RDM practices. By integrating RDM best practices into AI and ML training, researchers can enhance their understanding of methodologies, improve data handling and ethics, foster reproducibility, and gain public trust in these impactful computational methods.

The outcome of the Machine Learning Tutorial Series is aimed at integrating research data management (RDM) best practices with AI and ML tutorials to attract new users, engage existing ones, and showcase the capabilities of HPC computing technologies. Through the development of easily accessible, bilingual training assets, both researchers and support staff will be equipped to harness advanced computing and AI technology for accelerating discovery. This initiative plans to produce seminar and workshop materials covering six new topics, aligning with the DMP Assistant Data Management Plan framework to illustrate AI and ML techniques and modeling while enhancing existing content. These tutorials will guide learners through the process of accessing and cleaning open data for AI and ML model implementation, each session focusing on a new AI or ML model and highlighting both its advantages and limitations alongside RDM best practices throughout the research data lifecycle.

The training material provided in this repository consists of Jupyter Notebooks, datasets, and additional resources carefully curated by the uOttawa team. Each notebook is designed to provide a structured learning experience, combining theoretical explanations with hands-on exercises to reinforce understanding.

In each notebook you will see a short description of the training material, the learning objectives and the average time to complete, the necessary tools and documents you will need to complete the training, RDM best practices, and the step-by-step training content.

These series were developed by a team of scholars from the University of Ottawa. The development of the Machine Learning Series Training involved collaboration among scientific computing specialists, Jarno van der Kolk and Peter Darveau, and Felicity Tayler a specialist from the Data Literacy Research Institute focusing on Research Data Management, advisors, and research assistants. Led by a diverse team with expertise spanning scientific computing, AI training, and research data management, the initiative seeks to integrate best practices in research data management with AI and ML tutorials. With Julie St-Pierre, an advisor from the University of Ottawa’s research support and infrastructure team, the project ensures alignment with academic standards and aims to empower researchers and support staff with easily accessible, reusable training assets in both French and English.

## Index to the Tutorials
In this series of training, we cover a wide range of topics as follows:

### ML_cleaning_and_Regression
This tutorial focuses on optimizing data preparation for machine learning, specifically by merging bike traffic and weather data to predict bike traffic patterns based on weather conditions. Utilizing Open Data sources, we ensure data integrity and consistency, rectify any errors, and enhance the dataset with additional values for accuracy. The tutorial employs Linear Regression, the simplest machine learning model, to make predictions based on input data. Data is sourced from Ottawa's bike count data via their Open Data website and historical weather data from Environment Canada. These datasets, already downloaded and available in the tutorial repository, are combined to create training data.

### Decision Trees

This training contained three notebooks: This tutorial will delve into the functionality of the Decision Tree algorithm in prediction-making. Comprising three notebooks, each notebook delves into distinct applications of the Decision Tree and its associated Random Forest algorithm. Essentially, a Random Forest constitutes a compilation of Decision Trees.

#### Notebook 1 Decision Trees

This notebook will focus on analyzing data related to the Iris flower, a widely cultivated genus across various global temperature zones. With approximately 300 species, manual identification of these plants can be time-consuming. Therefore, the objective is to develop a model capable of predicting the iris flower's class based on its distinctive features. This entails accessing Open Data sources to obtain datasets containing information on different iris flower classes and their key attributes, ensuring data integrity and consistency. The tutorial will employ Decision Trees, a straightforward machine learning model, which operates by segregating data into groups akin to categorizing a population based on various attributes. This hierarchical structure aids in accurately predicting outcomes when new input data is introduced to the model.

#### Notebook 2 Random Forest

This tutorial explores the functionality of the Decision Tree algorithm in predicting classes of Iris flowers based on their features. With over 300 species, manual identification of Iris plants is time-consuming, hence the need for a predictive model. Accessing Open Data sources provides ample datasets for analysis, ensuring data integrity and enrichment. Utilizing Decision Trees, the tutorial demonstrates how this simple machine learning model partitions data into groups, facilitating accurate predictions when new data is introduced. Additionally, the tutorial extends to Random Forest models, comprising multiple decision trees for enhanced prediction accuracy. The datasets, procured from the University of California Irvine's Open Data website, are readily available in the tutorial repository for training and testing purposes.

#### Notebook 3 Random Forest + Noisy Datasets
This tutorial delves into the efficacy of Random Forest classifiers in enhancing predictions on noisy datasets, using the cleaned dataset from a Linear Regression tutorial as an example. While Linear Regression is a widely employed technique for modeling variable relationships, its assumption of linearity often falters in real-world datasets rife with noise, anomalies, or intricate nonlinear patterns. Consequently, linear regression may struggle to produce accurate predictions, as it tends to overfit noise rather than discern the underlying structure. Through this tutorial, the superiority of random forests over linear regression on noisy datasets is demonstrated. Random forests, an ensemble method, leverage the predictions of multiple decision trees to yield more robust and generalized solutions. By employing the cleaned dataset containing anomalies and missing/incorrect values, learners gain insight into how random forests mitigate the impact of noise and other issues, thereby offering superior predictive performance.

### ML_naive_bayes
This tutorial provides an overview of the Naive Bayes Classifier, a machine learning technique used for pattern detection and prediction. It begins by revisiting the Iris flower dataset to introduce the basic steps of working with the Naive Bayes Classifier. Next, it applies the classifier to detect spam in SMS messages using the SMS Spam collection dataset from the UCI Machine Learning Repository, followed by multi-label classification using the CMU book dataset. Additionally, the tutorial illustrates a scenario where the Naive Bayes Classifier fails and explains the reasons behind it. By the end of this tutorial, participants will be able to grasp the concept of the Naive Bayes classifier, split data into training and testing sets, make predictions, evaluate classifier performance, identify spam, classify books, train a Gaussian Naive Bayes classifier for single or multiple labels, and utilize imputation techniques for handling missing data.

### Support Vector Machines (SVMs)
Support vector machines (SVMs) are robust machine learning models that utilize mathematical optimization to identify maximum margin hyperplanes for classification tasks. This training contained four notebooks: Regularization, Kernels, Deeper-Undertanding, and Noise_Red_Reduction.

#### Notebook 1: Regularization
In this notebook, we delve into Support Vector Machines (SVMs), focusing on the principle of maximizing the margin to achieve robust classification performance. SVMs excel in classification and regression tasks by identifying the optimal decision boundary that maximizes the separation between different classes' closest data points, known as support vectors. We explore SVMs' capability to handle both linearly and non-linearly separable patterns through kernel functions. Using the make_blobs dataset from scikit-learn, which generates synthetic data with well-defined clusters, we gain hands-on experience in training linear SVM models and visualizing decision boundaries. Additionally, we learn about regularization techniques and practice tuning regularization parameters to optimize model performance.

#### Notebook 2: Kernels
This notebook introduces kernels, which are functions that elevate data to a higher dimension for better separability. Kernels are vital in Support Vector Machines (SVMs) as they transform non-linear problems into linearly separable ones, enhancing classifier accuracy. Four popular SVM kernels include Linear, Polynomial, Radial Basis Function (RBF), and Sigmoid kernels. The project focuses on classifying Pulsar stars using SVM, tackling dispersed datasets through the kernel trick, enabling separation in higher-dimensional spaces. The dataset used is available from the University of California Irvine's Open Data website. It describes the periodic radio signals emitted by rotating pulsars, aiding in distinguishing true pulsars from interference. Learning objectives encompass understanding SVMs, kernels, implementation in Python with scikit-learn, kernel selection, tuning for optimal performance, and model evaluation through techniques like cross-validation.

#### Notebook 3: A Deeper Understanding
This notebook delves into SVMs, potent supervised ML algorithms for classification and regression tasks, tackling scenarios where data dispersion challenges linear separation. Using visual representations of datasets, it explores how diverse kernel functions in SVM classifiers affect decision boundaries and margins, offering practical insights beyond mathematical analysis. The tutorial utilizes the iris dataset from sklearn to exemplify these concepts. Participants will gain practical experience in implementing SVM kernels, understand kernel selection and tuning, and develop a tangible understanding of how different kernels enhance classification performance through visualizations.

#### Notebook 4: Noise_Red_Reduction
This notebook focuses on addressing noise and variance in data, essential challenges in real-world systems. Noise, arising from natural randomness and uncertainties, includes measurement errors and unmeasured influences. To combat variance, the tutorial explores how Random Forests employ ensemble modeling to reduce overfitting in SVM models. By averaging probabilistic predictions from an ensemble of SVM classifiers, Random Forests mitigate variance and enhance model performance, offering insights into ensemble learning techniques and the synergy between SVM and Random Forest classifiers in handling noisy data.

## Prerequisites:

Participants are expected to have:

* Basic knowledge of Python programming language.
* Familiarity with fundamental concepts in statistics and machine learning.
* Prior exposure to research data management practices is advantageous but not mandatory.

## Getting Started:

To begin your journey into the realm of research data management and machine learning, explore the notebooks available in our [GitHub repository](https://github.com/orgs/uOttawa-IT-Research-teaching/repositories).

Feel free to engage with the material, experiment with the code, and embark on a transformative learning experience in research data management and machine learning!

All notebooks have been created as Jupyter notebooks which are a blend of explanatory text and executable Python code. There are various ways to run these yourself. There are a few zero-configuration online platforms available:

* SyZyGy ([https://syzygy.ca/](https://syzygy.ca/))
  * An online platform that allows researchers from many different institutions to upload and run their own notebooks but disk space is limited to 1GB
* Alliance ([https://docs.alliancecan.ca/wiki/JupyterHub](https://docs.alliancecan.ca/wiki/JupyterHub))
  * Another online platform with more powerful machines than SyZyGy but you will need to request an account first.
* Google Colab ([https://colab.research.google.com/](https://colab.research.google.com/))
  * Jupyter notebooks are compatible with Google Colab.
* Amazon SageMaker ([https://aws.amazon.com/sagemaker/](https://aws.amazon.com/sagemaker/))
  * Jupyter notebooks are compatible with Amazon SageMaker.

If you want, you can also run the notebooks locally on your machine. Keep in mind that some of the notebooks might tax your machine quite a bit. This is especially true for the later notebooks.

To install locally, the easiest way is to use Anaconda or Miniconda ([https://www.anaconda.com/](https://www.anaconda.com/)). They have the same base, but Anaconda will install everything you could possibly need which includes Python, Jupyter, and many of the required Python packages. If you are pressed for disk space, then Miniconda might be a better option. Instructions for setting up Miniconda can be found here: [https://docs.anaconda.com/free/miniconda/index.html](https://docs.anaconda.com/free/miniconda/index.html)

Once Miniconda is installed, you can install Jupyter using

```
conda install -c conda-forge jupyterlab
```

Anaconda will already have Jupyter Lab included.

## Acknowledgment

These training modules were originally created for the uOttawa Scientific Computing teaching series and the RDM sections of the uOttawa Library RDM Services. The funding for this set of Machine Learning Trainings was supplied by Compute Ontario as an Open Educational Resource. The University of Ottawa holds ownership of this training series. This training is made available under the Creative Commons licence CC-BY 4.0, allowing for easy sharing and adaptation while ensuring proper attribution to the original creators.

## Support
Members of the University of Ottawa can open a TOPdesk ticket at [https://topdesk.uottawa.ca](https://topdesk.uottawa.ca) for assistance with machine learning projects or getting access to computational resources to run them.

For more assistance with computational resources which is also available for non-uOttawa members, see the Digital Research Alliance of Canada: [https://docs.alliancecan.ca/wiki/Technical_support](https://docs.alliancecan.ca/wiki/Technical_support)
