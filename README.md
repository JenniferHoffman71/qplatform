Qlytics and it's partner Global Risk Intelligence Inc. (GRI) are pleased to provide the following response to RFI Number: 70SBUR19I00000038. 

Information provided within this repository outlines Qlytics and GRI capabilities, details on IT projects developed using the Qlytics platform, a detailed overview of Qlytics microservices based AI Development platform, and how Qlytics and its Q-Platform meets and exceeds the requirements to; 
1. Automate the use of AI/ML 
2. Provide relationship discovery and mapping 
3. Provide dynamic fault-tolerant Machine and Deep Learning based data connectors. 
4. Provide integrated knowledge management and discovery portal. 
5. Provide a framework for intelligent data sourcing and collecting (scraping) data. 

For questions regarding the details in this repository please contact:

Brendan Reilly
Chief Technology Officer
Qlytics LLC, 
Tel:  +1 203-722-1209 
Email:  breilly@qlytics.com

We recognize that the landscape with which we are dealing changes quickly, and could result in the need for adjustments in the composition of the information provided within this repository.  We are excited about the prospects of supporting the U.S. Citizenship and Immigration Services (USCIS) Office of Information Technology and are open to continued communications regarding our business and technical collaboration.
_________________________________________________________________________

# Introduction
Qlytics is a single, full-stack AI Development Platform that enables new, faster, and more efficient ways of transforming existing human-driven tasks into machine driven operations.

A machine and deep learning system, Qlytics delivers automated, on-demand, secure, curated access to the API connected datasets, expert AI talent, machine & deep learning apps + algorithms, collaboration & project management tools, and enterprise security necessary to quickly automate and AI-enable businesses / processes and to help organizations extract insights and make decisions at the speed of machines.

As the first full-stack AI Development Platform, Qlytics overcomes the challenges of developing and deploying AI (using a Continuous (code) Integration/Continuous Delivery Pipeline) while simplifying and accelerating an organization’s AI automation journey. 

_________________________________________________________________________

# Architecture
The Qlytics Platform leverages a secure API driven, microservices based architecture that automates development workflows by instantly bringing together the – people, tools, resources and infrastructure needed to build advanced AI driven solutions. With 3rd party API integrations with Jira, Slack, Github, AWS and by leveraging more than 500 open source libraries and tools within its integrated platform Qlytics enables rapid deployment and secure management of AI/ML development and delivery.

![alt text](https://github.com/qlyticsllc/qplatform/blob/master/Qlytics%20Platform%20Architecture.png)

Qlytics platform is comprised of 7 microservices, integrated AI Applications, AI/ML Starter Kits and a set of integrated Algorithms that work together to provide a contextual workflow to automate the delivement and delivery of AI/ML driven solutions.

### Qlytics Microservices

Q-AUTH  -  Central Authentication Service (CAS) and user Identity & Access Management (IAM) Service.

Q-GATEWAY  -  A REST API based routing service that manage web requests between the different Q-Platform and 3rd party services (Includes Jira, Slack, Github, AWS integration)

Q-MANAGER  -  Project management and reporting service that integrates resources provided by other microservices.

AI TALENTHUB  -  Local and Global Talent Management Service.

COMPUTE  -  Cloud infrastructure management Service.

SUBSCRIPTION  -  A payment and subscription management service with Stripe integration.

DATA EXCHANGE  -  Service for publishing subscription based API accessible dataset at scale.


### Qlytics Applications

Q-DEEP-NLP  -  Automatically processes documents using a combination of Statistical and Deep-Learning approaches.

Q-DEEP-VISION  -  Computer vision application that combines a convolutional neural network, a framework for supervised learning and a user friendly interface to deliver the ability to detect, track and report on objects and actions within images and videos. 

### Qlytics AI Starter Kits
AI Starter Kits includes popular Python packages, pre-verified and scanned for vulernabilities and open-source licenses issues to ensure against outdated or vulnerable versions, incompatibility and improper licensing, so you can get up and running in minutes. The Qlytics Platform has (4) Integrated AI Starter Kits and the ability to Bring-Your-Own. Starter Kits include:

MACHINE LEARNING STARTER KIT - A Python based auto deployed Machine Learning based functional container (Docker, AMI) of pre-scanned open source tools and libraries including auto launched Jupyter Notebook. 

DEEP LEARNING STARTER KIT - A Python based auto deployed Deep Learning GPU based functional container (Docker, AMI) of pre-scanned open source tools and libraries including auto launched Jupyter Notebook and open-source tools and libraries.

SOURCE & COLLECT STARTER KIT  -  A Python based auto deployed Deep Learning GPU based functional container (Docker, AMI) of pre-scanned open source tools and libraries including auto launched Jupyter Notebook and open-source tools and libraries.

DATA SCIENCE STARTER KIT - A Python based auto deployed containerized (Docker, AMI) Data Science container of pre-scanned open source tools and libraries including H2O, Pandas, Sklearn, tensorflow, keras, matplotLib, boken, dask, elasticsearch, and more. 


### Qlytics Bots + Algorithms
The Qlytics Platform has integrated dozens of API accessible NLP, Computer Vision and Document processing Algorithms for incorporation into AI driven workflows. Standard Bots include Translation, Sentimate Analysis, Named Entity Recognition, Object Detenction, Word Vectorization, Part-of-speech tagging, Document Classification and others.

Cloud formation details: https://github.com/qlyticsllc/platform-deployment


_________________________________________________________________________

# Past Performances
The following projects have been delivered by Qlytics using the Q-Platform:

### Project 1  -  AI/ML Driven Counter Party Risk Application
Project Summary: Qlytics developed and delivered a AL/ML driven Application to calculate Counter Party Risk of Global Banks and all U.S financial institutions. This application sources and collects financial, market and controversial news data daily on 4,500+ U.S Banks and 12 large Global Financial Institutions. This project leveraged Qlytics Source and Collect (Scraping) Starter Kit, Q-Deep-NLP advanced launge processing framework, ML algorithms to calculate stock volitility and a custom built python based PD (Probability of Default) model. This solution collects more than 1 million datapoints per month and leverages a ML model to score Counter Party Risk for one of the largest stock exchanges in the world. 
Project Details: https://github.com/qlyticsllc/qplatform/past-performance/counter-party-risk

### Project 2  -  Environment, Social and Goverance (ESG) Rating Application
Project Summary: Qlytics developed and delivered a AL/ML driven Application to calculate corporate commitment to Environment, Social and Goverance (ESG). Leveraging Qlytics platform to source and collect (scrape) sustainability reports on 45,000 global companies, in over 50 countries. Using Qlytics Q-Deep-NLP advanced launge processing framework PDF reports are automatically procressed to extract target data. Over 400,000 documents in 19 languages have been collected and processed with daily updates delivered as API accessible datasets from the Qlytics platform's integrated Data Exchange. The solution leverages a Machine and Deep Learning based NLP app (Q-Deep-NLP), automated workflow management to extract key knowledgepoint from unstructured text documents. 
Project Details: https://github.com/qlyticsllc/qplatform/past-performance/esg

### Project 3  - Analyze Municiple Bond Documents with Advanced Natural Language Processing (NLP)
Project Summary: Qlytics developed and delivered a neuro-linguistic programming / natural language processing (NLP) based solution to automatically read and extract knowledge from large qualities (40,000+) Municipal Bond documents for one of the largest rating agencies in the world. The solution leverages a advanced web scrapper and Machine and Deep Learning based NLP app (Q-Deep-NLP) to automate the workflow management of PDF documents to extract key knowledge point from unstructured text documents. 
Project Details: https://github.com/qlyticsllc/qplatform/past-performance/muni-bonds

### Project 4  - Predict Fund Flows of Eletronic Traded Funds (ETF) 
Project Summary: Qlytics developed and delivered a ML based solution to track and predict fund flows of Eletronic Traded Funds (ETF) across all Electronic Traded Funds. Using advanced web scraping, ML and predictive analytics to collect and auto analyze ETF holdings and performance. This solution was built for one of the largest ETF issues in the world. 
Project Details: https://github.com/qlyticsllc/qplatform/past-performance/direxion


_________________________________________________________________________


# Related Additional Projects

### Project 1  - Deep Learning based Inventory Management with Computer Vision 
Project Summary: Qlytics developed a Deep Learning based (Tensorflow) Computer Vision based application to leverage custom-training object detection to track municiple inventory and assets. Built for a state Department of Transportation the solution processes real-time video and provides detailed reporting and advanced analysis features. 

### Project 2  -  Reduce the Global Requirement for Fossile Fuel using ML
Project Summary: Leveraging ML models and automated quanitative analytics, Qlytics developed a set of Python based models to predict power output from windmill farms for the largest power company in the world. Leveraging Qlytics Data Science AI Starter Kit, Qlytics delivered an API accessible mathimatic model that provides the ability to predict future power output.

### Project 3  - Medical Bill Analysis using NLP
Project Summary: Leveraging Qlytics Q-Deep-NLP Natural Language Processing App built a solution to extract medical billing details from unstructured PDF based medical documents for one of the largest healthcare providers in the world. 

### Project 4  - Improve Edler Care using AI/ML 
Project Summary: (Currently developing a AI/ML driven solution Help predict healthcare risk of elderly individuals enrolled in the Massachuesttes Office of Edler Affairs. Using the Qlytics platform Q-Deep-NLP and AI Starter kits to provide and autmated workflow of 


# Additional details 
Additional content in this repository includes:

1. Q-Platform User Guide (https://qlytics-demo.readthedocs-hosted.com/en/latest/q-platform/index.html)

2. Q-Deep-NLP User Guide (Machine and Deep Learning NLP Framework) (https://qlytics-demo.readthedocs-hosted.com/en/latest/q-deep-nlp/index.html)

3. Q-Deep-Vision User Guide (Deep Learning Computer Vision Framework) https://qlytics-demo.readthedocs-hosted.com/en/latest/q-deep-vision/index.html

4. CloudFormation Details (https://github.com/qlyticsllc/platform-deployment)
