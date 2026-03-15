# AlgorithmsForMassiveData_Project

The following project was implemented using Python 3 for the course of Algorithms For Massive Data, module taught at the Master in «Data Science for Economics» at the Università degli Studi di Milano.
The primary task was to implement a detector of pairs of similar abstract for scientific papers.

## Methodology

The project follows these steps:

### 1. Data preprocessing
- Removal of missing abstracts
- Tokenization of text
- Stopword removal
- Conversion of tokens into sets

### 2. Exact similarity computation
Jaccard similarity is first computed directly on a subset of documents.

### 3. MinHash approximation

### 4. Locality Sensitive Hashing (LSH)

### 5. Evaluation
The approximation quality of MinHash is evaluated by comparing:

- exact Jaccard similarity
- MinHash estimated similarity

### 6. Scalability analysis

## Results
