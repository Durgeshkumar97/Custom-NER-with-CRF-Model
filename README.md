# NER with CRF Model for Medical Text

## Overview

This repository hosts the codebase and documentation for an NLP assignment focusing on Named Entity Recognition (NER) utilizing a Conditional Random Field (CRF) model. The objective is to process medical text data, identify diseases, and predict their corresponding treatments. The repository is structured to guide through the various steps of the assignment.

## Repository Structure:

1. **Data Processing:**
   - **File:** `data_processing.ipynb`
   - **Description:** Preprocesses tokenized datasets (`train_sent`, `test_sent`, `train_label`, `test_label`), constructs sentences, and prepares label lines.

2. **Concept Identification:**
   - **File:** `concept_identification.ipynb`
   - **Description:** Utilizes spaCy for Part-of-Speech (PoS) tagging to identify top concepts (NOUN or PROPN).

3. **CRF Feature Definition:**
   - **File:** `crf_feature_definition.ipynb`
   - **Description:** Defines features for the CRF model, including PoS tags, preceding words, and sentence boundaries.

4. **Feature and Label Extraction:**
   - **File:** `feature_label_extraction.ipynb`
   - **Description:** Extracts features' values for sentences and labels from preprocessed lines.

5. **Model Building:**
   - **File:** `model_building.ipynb`
   - **Description:** Constructs the CRF model for a custom NER application using defined features and target variables.

6. **Model Evaluation:**
   - **File:** `model_evaluation.ipynb`
   - **Description:** Evaluates the CRF model, predicting labels, and calculating the F1 score.

7. **Disease and Treatment Identification:**
   - **File:** `disease_treatment_identification.ipynb`
   - **Description:** Creates logic to predict treatments for diseases in the `test` dataset.

8. **Commented Jupyter Notebook:**
   - **File:** `assignment_solution.ipynb`
   - **Description:** A well-commented notebook providing a step-by-step guide for the entire assignment.

## Instructions:

1. **Download Datasets:**
   - [Train Sentence Dataset (`train_sent`)](#)
   - [Train Label Dataset (`train_label`)](#)
   - [Test Sentence Dataset (`test_sent`)](#)
   - [Test Label Dataset (`test_label`)](#)

2. **Execution:**
   - Follow the notebooks sequentially for smooth data processing, feature definition, model building, and evaluation.

3. **Analysis:**
   - Dive into the logic for disease and treatment identification using the custom NER model.

4. **Inquiries:**
   - For any questions, refer to the assignment solution video segments or contact the instructor.

This repository serves as a comprehensive guide to mastering NER applications in the healthcare domain. Explore the world of medical text processing with confidence!
