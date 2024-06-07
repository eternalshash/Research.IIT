# Intestinal Function Prediction Using Machine Learning

## Project Overview

This project aims to develop a machine learning (ML) model to predict intestinal function based on gut bacteria, with a particular focus on patients with Inflammatory Bowel Diseases (IBD) such as Crohn’s disease and ulcerative colitis. These conditions significantly affect drug absorption and metabolism, and our model seeks to elucidate the role of the microbiome in these processes to optimize and personalize treatment strategies.

## Applicant Information
- **Name:** Shashwat Choudhry
- **Major:** Computer Engineering
- **Year:** Rising Junior at Illinois Institute of Technology (IIT)
- **Faculty Mentor:** Dr. Abhinav Bhushan, Armour College of Engineering

## Project Description

### Background Information and Problem Statement

Recent studies have highlighted how specific bacterial genes can influence drug absorption and metabolism in IBD patients. Despite these advances, there remains a significant gap in understanding which bacterial species are beneficial or detrimental in the context of IBD and how they affect drug response. This project leverages RNA sequencing data and bacterial species abundance data from IBD patient samples to build predictive models.

### Objectives and Scientific Hypothesis

The primary goal is to develop an AI/ML model to predict the impact of different bacterial species on drug metabolism and absorption in IBD patients. The hypothesis is that interactions between certain bacterial species and human genes related to drug metabolism pathways can predict the pharmacokinetic profiles of medications used in IBD treatment.

### Methodology and Approach

#### Data Collection and Analysis
- Utilize RNA sequencing data and bacterial species abundance data from IBD patient samples.

#### Initial Modeling
- Identify gene expression changes relevant to drug absorption and metabolism, correlating these changes with bacterial species prevalence.

#### Advanced Analytical Techniques
- Implement Principal Component Analysis (PCA) to identify key bacterial components impacting gene pathways.

#### Model Development and Testing
- Construct and refine AI/ML models, including regression models and neural networks, to accurately predict bacterial impacts on drug absorption and metabolism.

### Implementation Steps

1. **Understanding the Data**
   - Analyze the given multi-dimensional spreadsheet data to understand variability and gene expression changes.

2. **Implementing Regression Model (Part 1)**
   - Create a preliminary clustering and association-based model using supervised learning techniques.

3. **Implementing ML Model (Part 2)**
   - Develop a Neural Network based on existing data, transitioning to unsupervised learning to refine the model.

4. **Network Testing**
   - Compare the performance of Dependency-based Convolutional Neural Networks (D-CNN) and Recurrent Neural Networks (RNN) for the dataset.

5. **Scalability**
   - Evaluate the scalability of both RNN and D-CNN approaches for large-scale data.

6. **Model Creation and Verification**
   - Develop, optimize, and verify the model over a three-semester cycle, culminating in an integrated and clinically relevant predictive model.

### Timeline

1. **Summer Semester**
   - Preliminary testing and development of a basic regression and clustering model.
   - Implementation of D-CNN to handle structured data and test scalability.

2. **First Semester of Armour Research Cycle**
   - Focus on data cleaning, preprocessing, and creating a baseline for model performance.
   - Begin optimization phase for both RNN and D-CNN models.

3. **Second Semester of Armour Research Cycle**
   - Final testing and model validation.
   - Integration of RNN and D-CNN models and iterative feedback loop for continuous learning.

## Expected Contributions and Impact

This research aims at the treatment paradigms for IBD by clarifying the role of the microbiome in drug absorption and metabolism. The AI/ML model developed could personalize and optimize treatment strategies, significantly enhancing patient outcomes and providing a substantial contribution to healthcare in gastrointestinal diseases.

## Progress Showcase

The progress of this project will be showcased at the Armour R&D Expo and the Chicago Area Undergraduate Research Symposium (CAURS).

## Contributing

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

This project is supported by Dr. Abhinav Bhushan and the Armour College of Engineering at IIT. 

## Contact

For any questions or inquiries, please contact Shashwat Choudhry at choudhryshashwat29@gmail.com

---
