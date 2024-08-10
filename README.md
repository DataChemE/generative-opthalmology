# Generative AI for Ophthalmological Image Synthesis

## Project Overview

This repository contains a Jupyter notebook that demonstrates the use of generative AI techniques to create synthetic ophthalmological images based on the Brazilian Multilabel Ophthalmological Dataset (BRSET). The project aims to develop models for both classification and generation of high quality, diverse eye images.

## Goals

1. Create a high-performance classifier for ophthalmological conditions using the BRSET dataset.
2. Implement a StyleGAN2 based generator capable of producing realistic eye images.
3. Discover and visualize attributes that are important for classifying various eye conditions.
4. Generate synthetic images that could potentially be used to augment existing datasets.

## Methodology

The project follows a multi-step process inspired by the paper "Using generative AI to investigate medical imagery models and datasets" (Lang et al., 2024):

1. Image Classification
2. Generative Model Development
3. Attribute Discovery
4. Analysis and Interpretation

## Data Source

The data used in this project is from the Brazilian Multilabel Ophthalmological Dataset, available on Physionet. Due to data use agreements, the dataset is not included in this repository.

## Ethical Considerations

This project acknowledges the ethical implications of generating synthetic medical data. All generated images should be clearly labeled as synthetic and not used for diagnostic purposes without extensive validation.

## Repository Contents

This repository contains a single Jupyter notebook that runs through the entire workflow, including model training, image generation, and analysis.

## Getting Started

To explore this project, simply open the Jupyter notebook in the repository. Please note that you will need to separately acquire access to the BRSET dataset from Physionet to run the notebook fully.

## Note

This is not a typical cloneable repository, but rather a demonstration of the research methodology and findings. The models trained on the BRSET are shared with the research community in compliance with the data use agreement.

