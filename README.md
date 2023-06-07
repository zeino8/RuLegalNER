# RuLegalNER Dataset

## Description

Welcome to the RuLegalNER dataset repository! This repository contains the RuLegalNER dataset, which is designed to study the generalization ability of named entity recognition models trained on automatically annotated datasets. The dataset comprises Russian legal documents that have been annotated with more than 20 classes of named entities. However, it's important to note that the annotation coverage is sparse, and not all legal named entities present in the documents are annotated.

To create this dataset, we specifically selected five classes for inclusion: Individual person, legal entity, Penalty, Crime, and Law. The annotation process was performed using a rule-based system provided by TAG Consulting company. This dataset aims to evaluate the performance of models on unseen named entities, as we incorporated low-frequency entities that were exclusively reserved for the validation and test stages.

## Dataset Information

The RuLegalNER dataset consists of a sample of 100,000 Russian legal documents. Within this dataset, there are a total of 860 unique named entities. Notably, 289 of these entities appear only in the test set, resulting in a total of 777 occurrences of unseen entities in the test set.

## Usage
T
he RuLegalNER dataset can be utilized for various purposes, including but not limited to:

- Training and evaluating named entity recognition models in the legal domain.
- Studying the generalization ability of models on unseen named entities.
- Conducting research on rule-based systems and their effectiveness in legal text annotation.

## Dataset Access

You can download the dataset using the following link: https://drive.google.com/drive/folders/1g5H3LsgZnYdPhtZntYFI4eUzbnzdXULf?usp=sharing
