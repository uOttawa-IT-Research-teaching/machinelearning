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

The outcome of the Machine Learning Tutorial Series is aimed at integrating research data management (RDM) best practices with AI and ML tutorials to attract new users, engage existing ones, and showcase the capabilities of HPC computing technologies. Through the development of easily accessible, bilingual training assets, both researchers and support staff will be equipped to harness advanced computing and AI technology for accelerating discovery. This initiative plans to produce seminar and workshop materials covering six new topics, aligning with the DMP Assistant Data Management Plan framework to illustrate AI and ML techniques and modeling while enhancing existing content. These tutorials will guide learners through the process of accessing and cleaning open data for AI and ML model implementation, each session focusing on a new AI or ML model and highlighting both its advantages and limitations alongside RDM best practices throughout the research data life cycle.

The training material provided in this repository consists of Jupyter Notebooks, datasets, and additional resources carefully curated by the uOttawa team. Each notebook is designed to provide a structured learning experience, combining theoretical explanations with hands-on exercises to reinforce understanding.

In each notebook you will see a short description of the training material, the learning objectives and the average time to complete, the necessary tools and documents you will need to complete the training, RDM best practices, and the step-by-step training content.

These series were developed by a team of scholars from the University of Ottawa. The development of the Machine Learning Series Training involved collaboration among scientific computing specialists, Jarno van der Kolk and Peter Darveau, and Felicity Tayler a specialist from the Data Literacy Research Institute focusing on Research Data Management, advisors, and research assistants. Led by a diverse team with expertise spanning scientific computing, AI training, and research data management, the initiative seeks to integrate best practices in research data management with AI and ML tutorials. With Julie St-Pierre, an advisor from the University of Ottawa’s research support and infrastructure team, the project ensures alignment with academic standards and aims to empower researchers and support staff with easily accessible, reusable training assets in both French and English.

## Index to the Tutorials

In this series of training, we cover the following topics:

* [Data cleaning and linear regression](https://github.com/uOttawa-IT-Research-teaching/ML_cleaning_and_regression)
* [K-nearest neighbours](https://github.com/uOttawa-IT-Research-teaching/ML_k-nearest-neightbours)
* [Decision trees and random forests](https://github.com/uOttawa-IT-Research-teaching/DecisionTrees)
* [Support vector machines](https://github.com/uOttawa-IT-Research-teaching/SVM)
* [Naive Bayes](https://github.com/uOttawa-IT-Research-teaching/ML_naive_bayes)
* [Natural language processing](https://github.com/uOttawa-IT-Research-teaching/ML_Natural_Language_Processing)
* [Introduction to deep and convolutional neural networks](https://github.com/uOttawa-IT-Research-teaching/DNN-CNN_Intro)
* [DeepLearning with CNN](https://github.com/uOttawa-IT-Research-teaching/DeepLearning)
* [Transfer learning](https://github.com/uOttawa-IT-Research-teaching/TransferLearning_CNN)
* [Dataset analysis, model shortlisting and model determination](https://github.com/uOttawa-IT-Research-teaching/ML_Dataset_analysis_and_shortlisting)

## Prerequisites:

Participants are expected to have:

* Very basic knowledge of Python programming language.
* Prior exposure to research data management practices is advantageous but not mandatory.

## Getting Started:

To begin your journey into the realm of research data management and machine learning, explore the notebooks available in our [GitHub repository](https://github.com/orgs/uOttawa-IT-Research-teaching/repositories) or use the direct links from the index above.

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

## Acknowledgment

These training modules were originally created for the uOttawa Scientific Computing teaching series and the RDM sections of the uOttawa Library RDM Services. The funding for this set of Machine Learning Trainings was supplied by Compute Ontario as an Open Educational Resource. The University of Ottawa holds ownership of this training series. This training is made available under the Creative Commons licence CC-BY 4.0, allowing for easy sharing and adaptation while ensuring proper attribution to the original creators.

## Support
Members of the University of Ottawa can open a TOPdesk ticket at [https://topdesk.uottawa.ca](https://topdesk.uottawa.ca) for assistance with machine learning projects or getting access to computational resources to run them.

For more assistance with computational resources which is also available for non-uOttawa members, see the Digital Research Alliance of Canada: [https://docs.alliancecan.ca/wiki/Technical_support](https://docs.alliancecan.ca/wiki/Technical_support)
