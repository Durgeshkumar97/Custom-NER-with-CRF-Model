# Named Entity Recognition (NER) with CRF Model for Medical Text

Welcome to the repository dedicated to Named Entity Recognition (NER) using a state-of-the-art Conditional Random Field (CRF) model tailored for medical text analysis. This repository encapsulates a sophisticated framework and comprehensive documentation for an NLP assignment meticulously designed to identify diseases and predict their corresponding treatments.

## Overview

Our paramount goal is to meticulously process medical text data, effectively extract pertinent entities such as diseases, and predict their corresponding treatments with utmost accuracy. The repository is meticulously structured to seamlessly guide you through each intricate step of this challenging assignment.

## Repository Structure

1. **Data Processing:**
   - **File:** `data_processing.ipynb`
   - **Description:** Impeccably preprocesses tokenized datasets (`train_sent`, `test_sent`, `train_label`, `test_label`), meticulously constructs sentences, and prepares label lines with exacting precision.

2. **Concept Identification:**
   - **File:** `concept_identification.ipynb`
   - **Description:** Leveraging advanced techniques, including spaCy for Part-of-Speech (PoS) tagging, to discern top concepts (NOUN or PROPN) with unparalleled accuracy and efficiency.

3. **CRF Feature Definition:**
   - **File:** `crf_feature_definition.ipynb`
   - **Description:** Defines a comprehensive suite of features for the CRF model, encompassing PoS tags, preceding words, and sentence boundaries, meticulously crafted to enhance model performance.

4. **Feature and Label Extraction:**
   - **File:** `feature_label_extraction.ipynb`
   - **Description:** Painstakingly extracts feature values for sentences and labels from preprocessed lines, ensuring the utmost fidelity and accuracy in data representation.

5. **Model Building:**
   - **File:** `model_building.ipynb`
   - **Description:** Artfully constructs the CRF model for a bespoke NER application, leveraging meticulously defined features and target variables, setting a new standard in model sophistication and efficacy.

6. **Model Evaluation:**
   - **File:** `model_evaluation.ipynb`
   - **Description:** Rigorously evaluates the CRF model, expertly predicting labels and calculating the F1 score with unwavering precision, ensuring the highest standards of model performance assessment.

7. **Disease and Treatment Identification:**
   - **File:** `disease_treatment_identification.ipynb`
   - **Description:** Devises intricate logic to predict treatments for diseases in the `test` dataset, showcasing unparalleled expertise in the domain of medical text analysis.

8. **Commented Jupyter Notebook:**
   - **File:** `assignment_solution.ipynb`
   - **Description:** A meticulously annotated notebook providing a step-by-step guide, replete with insightful commentary, enabling seamless comprehension and replication of the entire assignment.

## Instructions

1. **Download Datasets:**
   - Train Sentence Dataset (`train_sent`)
   - Train Label Dataset (`train_label`)
   - Test Sentence Dataset (`test_sent`)
   - Test Label Dataset (`test_label`)

2. **Execution:**
   - Follow the notebooks sequentially, meticulously adhering to the prescribed steps for smooth data processing, feature definition, model building, and evaluation.

3. **Analysis:**
   - Delve deep into the intricate logic underpinning disease and treatment identification, showcasing a profound understanding of the intricacies of medical text analysis.

