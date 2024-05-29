# Machine Learning Tutorial Series

Welcome to the Bilingual (French and English) Machine Learning Tutorial Series published by uOttawa IT Research and Teaching!

Experiment with code, and embark on a transformative learning experience in RDM, AI & ML!

## Collaborators

The Machine Learning Tutorial Series is a significant contribution to the AI & ML training materials available to the academic research community in Canada and beyond. This bilingual resource was developed to raise awareness, understanding, and utilization of Artificial Intelligence (AI) and Machine Learning (ML) within our University of Ottawa research community, but with the support of Compute Ontario funding these tutorials will be appreciated by researchers affiliated with many institutions of higher education.

The Machine Learning Tutorial Series involved a collaborative effort from a team consisting of Scientific Computing specialists; a Librarian from the Data Literacy Research Institute with expertise in Research Data Management; advisors accross disciplines; and research assistants with Digital Humanities experience. This combination of expertise spanning scientific computing, AI training, research data management, and multiple disciplinary perspectives, integrates best practices in Research Data Management with AI and ML tutorials. With an advisor from the University of Ottawa’s research support and infrastructure team, the project aligns with academic standards and empowers researchers and research support staff with easily accessible, reusable training assets in both French and English.

We use the CRediT Contributor Role Taxonomy to acknowledge authorship roles on this Tutorial Series. The participants agreed to be credited for their contributions during the collaborative document creation process and were reminded of their role as authors prior to the document's publication.

Project lead, conceptualization and writing : Jarno van der Kolk, PhD, Senior Scientific Computing Specialist (University of Ottawa)

AI training expert, writing: Peter Darveau P. Eng. CED - Scientific Computing Support / Developer (University of Ottawa)

Editor, RDM expert, writing : Felicity Tayler, MLIS, PhD, Outreach Director \| DLRI and Research Data Management Librarian (University of Ottawa)

Advisor: Julie St-Pierre, PhD Associate Vice-President, Research Support and Infrastructure

Research assistant, review: Farinaz Basmechi, PhD

Training materials coordinator, review: François Thibeault \| DLRI

Translator: Matthieu Trudeau

## Target Audience:
This training series is created for:

* Researchers, scientists, and data practitioners involved in data-intensive research projects.
* Graduate students, postgraduate researchers, and academic faculty and administrators seeking to enhance their data management and analysis skills.
* Professionals interested in leveraging machine learning techniques for research data analysis and discovery.

## How Does This Open Educational Learning Resource Work?
This tutorial series addresses three key gaps in understanding AI and machine learning (ML) methodologies: 
* Providing an introduction to AI and ML models,
* Preparing data for these models, and
* Incorporating research data management (RDM) practices into AI and ML-enabled methodologies.

While AI and ML are recognized for their potential to automate tasks, identify patterns in data, and assist with analysis, many researchers struggle to apply these computational methods effectively to their research due to several challenges. These challenges include the complexity of selecting the appropriate model for their data; the common omission of data cleaning processes, resulting in mismatches between learned models and real-world data; and the separation of AI and ML techniques from RDM practices. By integrating RDM best practices into AI and ML training, researchers can enhance their understanding of methodologies, improve data handling and project management to reduce bias and respect ethics protocols; foster reproducibility; and gain public trust in these impactful computational methods.

The training material provided in this repository consists of Jupyter Notebooks, datasets, and additional resources carefully curated by the uOttawa team. Each notebook is designed to provide a structured learning experience, combining theoretical explanations with hands-on exercises to reinforce understanding.

In each notebook you will see a short description of the training material, the learning objectives and the average time to complete, the necessary tools and documents you will need to complete the training, RDM best practices, and the step-by-step training content.

This Series began with four core Tutorials. We will continue to produce seminar and workshop materials covering six new topics, aligning with the DMP Assistant Data Management Plan framework to illustrate AI and ML techniques and modeling. These tutorials will guide learners through the process of accessing and cleaning open data for AI and ML model implementation, each session focusing on a new AI or ML model and highlighting both its advantages and limitations alongside RDM best practices throughout the research data life cycle.

## Index to the Tutorials

In this Tutorial Series, we cover the following topics:

* [Data cleaning and linear regression](https://github.com/uOttawa-IT-Research-teaching/ML_cleaning_and_regression)
* [Decision trees and random forests](https://github.com/uOttawa-IT-Research-teaching/DecisionTrees)
* [Support vector machines](https://github.com/uOttawa-IT-Research-teaching/SVM)
* [Naive Bayes](https://github.com/uOttawa-IT-Research-teaching/ML_naive_bayes)

Here is the structure of the Machine Learning Tutorial Series (MLTS):
![image](https://github.com/uOttawa-IT-Research-teaching/machinelearning/assets/49539567/63fd90aa-50c1-4336-bf2c-b9a37ac5e63b)



This training followed the RDM file naming best practices to increase the discoverability of our data. 




To name our files we use the acronym of training as follows:  

Machine Learning Tutorial Series (**MLTS**):
Data Cleaning and Linear Regression (**DCRF**) 
Decision Trees and Random Forests (**DTRF**)
Support Vector Machines (**SVM**)
Naive Bayes (**NB**)


We implemented the following pattern for the file naming:



Project_date_AbbreviationofRelevantTraining_ContentDescription_Languageversion_Version.ext



More Tutorials will be added to this list as they become available, but since we teach these as regular training sessions on campus, we will give you a sneak peek at our working training materials, as we go! These materials are English-language only for the moment:

* [K-nearest neighbours](https://github.com/uOttawa-IT-Research-teaching/ML_k-nearest-neightbours)
* [Natural language processing](https://github.com/uOttawa-IT-Research-teaching/ML_Natural_Language_Processing)
* [Introduction to deep and convolutional neural networks](https://github.com/uOttawa-IT-Research-teaching/DNN-CNN_Intro)
* [DeepLearning with CNN](https://github.com/uOttawa-IT-Research-teaching/DeepLearning)
* [Transfer learning](https://github.com/uOttawa-IT-Research-teaching/TransferLearning_CNN)
* [Dataset analysis, model shortlisting and model determination](https://github.com/uOttawa-IT-Research-teaching/ML_Dataset_analysis_and_shortlisting)


## Prerequisites:

Participants are expected to have:

* Very basic knowledge of Python programming language.
* Prior exposure to basic RDM best practices is advantageous but not mandatory.

## Getting Started:

To begin your journey into the realm of RDM, AI and ML, explore the notebooks available in our [GitHub repository](https://github.com/orgs/uOttawa-IT-Research-teaching/repositories) or use the direct links from the index above.

Feel free to engage with the material, experiment with the code, and embark on a transformative learning experience in RDM, AI & ML!

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

If you chose to install Miniconda instead of Anaconda, you can install Jupyter using

```
conda install -c conda-forge jupyterlab
```

## Acknowledgment

These training modules were originally created for the uOttawa Scientific Computing teaching series and the RDM sections of the uOttawa Library RDM Services. The funding for the Machine Learning Tutorial Series was supplied by Compute Ontario, to be published as an Open Educational Resource. The University of Ottawa holds ownership of this training series. This training is made available under the Creative Commons licence CC-BY 4.0, allowing for easy sharing and adaptation while ensuring proper attribution to the original creators.

## Support
Members of the University of Ottawa can open a TOPdesk ticket at [https://topdesk.uottawa.ca](https://topdesk.uottawa.ca) for assistance with machine learning projects or getting access to computational resources to run them.

For more assistance with computational resources which is also available for non-uOttawa members, see the Digital Research Alliance of Canada: [https://docs.alliancecan.ca/wiki/Technical_support](https://docs.alliancecan.ca/wiki/Technical_support)
