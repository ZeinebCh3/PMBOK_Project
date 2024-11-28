# PMBOK_Project

This project explores the use of AI and cognitive techniques to extract, analyze, and process information from Project Management Body of Knowledge. By leveraging Natural Language Processing (NLP), Knowledge Graphs, and document analysis tools, this project aims to automate and enhance understanding from structured and unstructured data.

---

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Contributors](#contributors)
3. [Dataset Description](#dataset-description)
4. [Installation](#installation)
5. [How to Use](#how-to-use)
6. [Features](#features)
7. [Contributing](#contributing)
8. [License](#license)

---

## **Project Overview**
### **Objective**
This project uses modern AI and cognitive computing techniques to:
- Extract text and metadata from PDF and other document formats.
- Apply NLP methods to process and analyze extracted information.
- Build knowledge representations (like graphs) to better organize and query the data.

### **Key Technologies**
- **NLP**: Spacy, NLTK
- **Document Processing**: PyPDF2, pdfplumber
- **Knowledge Representation**: rdflib, owlready2
- **Visualization**: wordcloud, matplotlib

---

## **Contributors**
- Salma BELHADJ ALI
- Islem SAOUDI
- Arij M.

---

## **Dataset Description**
The project operates on a dataset of documents (e.g., PDFs) that are read, processed, and analyzed. These documents can include:
- Business reports
- Research articles
- Any other structured or unstructured data sources

---

## **Installation**
### **Requirements**
To run this project, you need:
- Python 3.7 or above
- Jupyter Notebook or Google Colab

### **Libraries**
Install the following libraries before running the notebook:
- `spacy`
- `rdflib`
- `PyPDF2`
- `owlready2`
- `wordcloud`
- `pdfplumber`

Install them using pip:
```bash
pip install spacy rdflib PyPDF2 owlready2 wordcloud pdfplumber
```

Download NLTK and Spacy models:
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
nltk.download('omw-1.4')
nltk.download('stopwords')
nltk.download('averaged_perceptron_tagger')

# Download Spacy model
!python -m spacy download en_core_web_sm
```

---

## **How to Use**
1. **Clone this Repository**:
   ```bash
   git clone https://github.com/your-username/ai-cognition-project.git
   ```
2. **Navigate to the Folder**:
   ```bash
   cd ai-cognition-project
   ```
3. **Open the Notebook**:
   ```bash
   jupyter notebook Group6_5DS3&4_PMBOK6_Project.ipynb
   ```
4. **Follow the Notebook Steps**:
   - Install necessary libraries.
   - Load and process your dataset.
   - Perform NLP and analysis.

---

## **Features**
- **Text Extraction**:
  - Extracts text and metadata from PDF documents.
- **Natural Language Processing**:
  - Tokenization, POS tagging, and Named Entity Recognition.
- **Knowledge Graph Construction**:
  - Uses `rdflib` and `owlready2` to create and query knowledge graphs.
- **Visualization**:
  - Word clouds and charts for insights from processed text.


