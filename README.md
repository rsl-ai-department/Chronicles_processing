# Chronicles_processing

# README

## Overview

This repository contains code for clustering scan images of "Book Chronicles", extract bibliographic records from json-documents, got with Yandex-OCR, generating data, and performing semantic entities on the records using a Large Language Model (LLM). The goal is to facilitate the organization and analysis of bibliographic data for users in library with research and academic purposes.

## Features

- Clustering: Group similar scan pages of "Book Chronicles" using clustering algorithms.
- Text Block Extraction: Isolate individual bibliographic entries from words and their coordinates on pages.
- Data Generation: Create dataframe with bibliographic data for testing and validation.
- Semantic Entities Identification: Identify and extract entities (e.g., authors, titles, years, journals, registration codes) within bibliographic records using LLM.

## Requirements

- Python 3.7 or higher
- Required libraries:
  - numpy
  - pandas
  - scipy
  - scikit-learn
  - umap-learn
  - img2vec-pytorch

## Installation

1. Clone the repository:
   
   git clone https://github.com/yourusername/repository-name.git
   cd repository-name
   

2. Install the required packages:
   
   pip install -r requirements.txt
   

## Usage
### Clustering
To cluster bibliographic records, look at:
1clustering.ipynb

### Text Block Extraction
To detect individual text blocks, look at:
2block_split_yandex.ipynb
3block_split_filtration.ipynb

### Data Creation
To create data with bibliographic records, look at:
4deep_filtration_and_get_dataset.ipynb

### Statistics
To look at data, use:
5statistics.ipynb

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the GPL-3.0 License. See the LICENSE file for details.

## Acknowledgments

- umap-learn (See: https://umap-learn.readthedocs.io/en/latest/) for clustering algorithms.

For any questions or feedback, please contact the repository owner.
