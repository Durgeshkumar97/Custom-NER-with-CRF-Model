# Custom-NER-with-CRF-Model
# NER with CRF Model for Medical Text

This repository contains code and documentation for a Natural Language Processing (NLP) assignment focused on Named Entity Recognition (NER) using a Conditional Random Field (CRF) model. The goal is to process medical text data, identify diseases, and predict their corresponding treatments. The assignment comprises eight key tasks, each contributing to the overall completion.

## Repository Structure:

1. **Data Processing:**
   - Jupyter notebook (`data_processing.ipynb`) for preprocessing tokenized datasets, constructing sentences, and preparing label lines.

2. **Concept Identification:**
   - Jupyter notebook (`concept_identification.ipynb`) using spaCy for Part-of-Speech (PoS) tagging to identify top concepts (NOUN or PROPN).

3. **CRF Feature Definition:**
   - Jupyter notebook (`crf_feature_definition.ipynb`) defining features for the CRF model, including PoS tags, preceding words, and sentence boundaries.

4. **Feature and Label Extraction:**
   - Jupyter notebook (`feature_label_extraction.ipynb`) extracting features' values for sentences and labels from preprocessed lines.

5. **Model Building:**
   - Jupyter notebook (`model_building.ipynb`) building the CRF model for custom NER application using defined features and target variables.

6. **Model Evaluation:**
   - Jupyter notebook (`model_evaluation.ipynb`) evaluating the CRF model by predicting labels and calculating F1 score.

7. **Disease and Treatment Identification:**
   - Jupyter notebook (`disease_treatment_identification.ipynb`) creating logic to get predicted treatments for diseases in the test dataset.

8. **Commented Jupyter Notebook:**
   - Reference notebook (`assignment_solution.ipynb`) with detailed comments, providing a step-by-step guide for the assignment.

## Instructions:

1. Download provided datasets (links in Readme).

2. Follow notebooks in order for data processing, feature definition, model building, and evaluation.

3. Explore logic for disease and treatment identification using the custom NER model.

4. For questions, refer to assignment solution video segments or contact the instructor.

This repository guides you through the assignment, offering insights into NER applications in the healthcare domain.
