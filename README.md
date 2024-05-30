# AI-900: Microsoft Azure AI Fundamentals Exam Preparation Guide

### 1. Describe Artificial Intelligence Workloads and Considerations (15–20%)

**Identify Features of Common AI Workloads:**

- **Content Moderation:**
  - **Purpose:** Automatically detect and filter inappropriate content to ensure community guidelines are maintained.
  - **Applications:** Social media platforms, online forums, video-sharing sites, and any user-generated content platforms.
  - **Techniques:** Uses techniques like image recognition, text analysis, and natural language processing.
  - **Tools:** Azure Content Moderator can scan text, images, and videos for offensive material, suggest edits, and block content.

- **Personalization:**
  - **Purpose:** Customize user experiences based on individual preferences and behaviors to enhance engagement and satisfaction.
  - **Applications:** E-commerce recommendations, content streaming services (e.g., Netflix, Spotify), personalized marketing emails.
  - **Techniques:** Machine learning models that analyze user data and behaviors to make predictions.
  - **Tools:** Azure Personalizer, which uses reinforcement learning to provide personalized experiences.

**Identify Specific AI Workloads:**

- **Computer Vision:**
  - **Definition:** Technology that allows computers to interpret and make decisions based on visual inputs.
  - **Applications:** Security and surveillance, autonomous vehicles, medical imaging (e.g., detecting tumors), retail (e.g., inventory management).
  - **Techniques:** Image classification, object detection, facial recognition, and OCR.

- **Natural Language Processing (NLP):**
  - **Definition:** Enables machines to understand, interpret, and generate human language.
  - **Applications:** Chatbots, sentiment analysis, language translation, voice assistants (e.g., Alexa, Google Assistant).
  - **Techniques:** Text analytics, language modeling, speech-to-text, text-to-speech, sentiment analysis.

- **Knowledge Mining:**
  - **Definition:** Extracting useful information from vast amounts of unstructured data.
  - **Applications:** Legal document analysis, enterprise search, customer service (e.g., identifying common issues), research.
  - **Techniques:** Text extraction, entity recognition, sentiment analysis, search indexing.
  - **Tools:** Azure Cognitive Search, which integrates various AI capabilities for extracting insights from data.

- **Document Intelligence:**
  - **Definition:** Automating the extraction of data from documents and understanding their content.
  - **Applications:** Invoice processing, contract analysis, form data extraction.
  - **Techniques:** OCR, natural language processing, and machine learning.
  - **Tools:** Azure Form Recognizer, which automates the extraction of text, key/value pairs, and tables from documents.

- **Generative AI:**
  - **Definition:** AI systems that can generate new content, such as text, images, or code, based on training data.
  - **Applications:** Content creation (e.g., articles, marketing copy), design (e.g., generating artwork), coding assistance.
  - **Techniques:** Deep learning models, especially generative adversarial networks (GANs) and transformer models.
  - **Tools:** Azure OpenAI Service, which provides access to advanced models for generating text, images, and more.

**Guiding Principles for Responsible AI:**

- **Fairness:**
  - **Goal:** Ensure AI systems do not perpetuate bias and are equitable across different user groups.
  - **Methods:** Bias detection and mitigation strategies, diverse training datasets.
  - **Considerations:** Regular audits, fairness metrics, and inclusive design practices.

- **Reliability and Safety:**
  - **Goal:** Develop AI systems that are robust, perform consistently, and handle errors gracefully.
  - **Methods:** Rigorous testing, fail-safes, continuous monitoring.
  - **Considerations:** Validating models with real-world data, ensuring systems can handle unexpected inputs.

- **Privacy and Security:**
  - **Goal:** Protect user data and maintain confidentiality throughout the AI lifecycle.
  - **Methods:** Data encryption, secure data storage, access controls, privacy-preserving algorithms.
  - **Considerations:** Compliance with regulations (e.g., GDPR), minimizing data retention, anonymizing data.

- **Inclusiveness:**
  - **Goal:** Make AI accessible and beneficial to all, considering diverse user needs and abilities.
  - **Methods:** Designing inclusive interfaces, ensuring accessibility standards.
  - **Considerations:** Engaging with diverse user groups during development, accessibility testing.

- **Transparency:**
  - **Goal:** Provide clear explanations of how AI systems make decisions and operate.
  - **Methods:** Explainable AI techniques, documentation, user-friendly explanations.
  - **Considerations:** Communicating model logic, decision-making processes, and limitations.

- **Accountability:**
  - **Goal:** Establish mechanisms for responsibility and oversight in AI development and deployment.
  - **Methods:** Maintaining logs, performing regular audits, implementing governance frameworks.
  - **Considerations:** Defining roles and responsibilities, establishing clear procedures for addressing issues.

### 2. Describe Fundamental Principles of Machine Learning on Azure (20–25%)

**Common Machine Learning Techniques:**

- **Regression:**
  - **Purpose:** Predicting continuous values based on input features.
  - **Applications:** Predicting house prices, stock prices, sales forecasting.
  - **Algorithms:** Linear regression, polynomial regression, support vector regression.
  - **Tools:** Azure Machine Learning, which provides tools for building, training, and deploying regression models.

- **Classification:**
  - **Purpose:** Assigning inputs to predefined categories or labels.
  - **Applications:** Email spam detection, disease diagnosis, image classification (e.g., identifying cats vs. dogs).
  - **Algorithms:** Logistic regression, decision trees, random forests, support vector machines, neural networks.
  - **Tools:** Azure Machine Learning, offering support for a variety of classification algorithms.

- **Clustering:**
  - **Purpose:** Grouping similar data points together without predefined labels.
  - **Applications:** Customer segmentation, market research, anomaly detection.
  - **Algorithms:** K-means, hierarchical clustering, DBSCAN.
  - **Tools:** Azure Machine Learning, which includes clustering algorithms and tools for data exploration.

- **Deep Learning:**
  - **Purpose:** Using neural networks with multiple layers to model complex patterns in data.
  - **Applications:** Image recognition, speech recognition, natural language processing.
  - **Algorithms:** Convolutional neural networks (CNNs), recurrent neural networks (RNNs), transformers.
  - **Tools:** Azure Machine Learning, Azure Deep Learning Virtual Machines, Azure Databricks.

**Core Machine Learning Concepts:**

- **Features and Labels:**
  - **Features:** Input variables used to make predictions.
  - **Labels:** The outcomes or targets being predicted.
  - **Example:** In a housing price prediction model, features might include the number of bedrooms, while the label is the price of the house.

- **Training and Validation Datasets:**
  - **Training Dataset:** Used to fit the machine learning model.
  - **Validation Dataset:** Used to tune model parameters and assess performance, ensuring the model generalizes well to new data.
  - **Example:** Splitting a dataset into 80% training and 20% validation to train and evaluate a model.

**Azure Machine Learning Capabilities:**

- **Automated Machine Learning (AutoML):**
  - **Purpose:** Simplifies the process of creating machine learning models by automating algorithm selection, hyperparameter tuning, and feature selection.
  - **Features:** User-friendly interface, support for various data types, model interpretability.
  - **Tools:** Azure Automated Machine Learning, which provides a drag-and-drop interface and APIs.

- **Data and Compute Services:**
  - **Purpose:** Provide scalable infrastructure for data processing, model training, and deployment.
  - **Features:** Scalable compute resources, integration with data storage solutions, support for distributed training.
  - **Tools:** Azure Machine Learning Compute, Azure Databricks, Azure Data Lake Storage.

- **Model Management and Deployment:**
  - **Purpose:** Manage the lifecycle of machine learning models, from development to deployment and monitoring.
  - **Features:** Model versioning, deployment to cloud or edge, monitoring and logging, integration with CI/CD pipelines.
  - **Tools:** Azure Machine Learning, Azure Kubernetes Service for deploying models as scalable web services.

### 3. Describe Features of Computer Vision Workloads on Azure (15–20%)

**Types of Computer Vision Solutions:**

- **Image Classification:**
  - **Purpose:** Categorizing images into predefined classes.
  - **Applications:** Identifying objects in images (e.g., classifying animals, products), medical imaging (e.g., detecting diseases).
  - **Techniques:** Convolutional neural networks (CNNs).
  - **Tools:** Azure Custom Vision, which allows users to build and deploy custom image classification models.

- **Object Detection:**
  - **Purpose:** Identifying and locating objects within an image.
  - **Applications:** Autonomous vehicles (detecting pedestrians and other vehicles), security (identifying threats), retail (inventory management).
  - **Techniques:** CNNs, region-based convolutional neural networks (R-CNNs).
  - **Tools:** Azure Custom Vision, Azure AI Vision.

- **Optical Character Recognition (OCR):**
  - **Purpose:** Converting images of text into machine-readable text.
  - **Applications:** Digitizing printed documents, extracting text from images for data entry automation.
  - **Techniques:** Deep learning-based text recognition.
  - **Tools:** Azure AI Vision, which provides OCR capabilities.

- **Facial Detection and Analysis:**
  - **Purpose:** Recognizing and analyzing facial features, emotions, and identities.
  - **Applications:** Security (facial recognition for access control), retail (analyzing customer emotions), social media (tagging people in photos
