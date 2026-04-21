# Drug-Drug Interaction Extraction from Biomedical Text using R-BioBERT with BiLSTM

## Overview
This project focuses on automatically identifying and classifying **Drug-Drug Interactions (DDIs)** from biomedical and clinical text using advanced **Natural Language Processing (NLP)** and **Deep Learning** techniques. Drug interactions are critical in healthcare, as combining medications can lead to harmful side effects or reduced effectiveness.

The proposed system leverages **R-BioBERT**, a biomedical domain-specific transformer model, combined with **BiLSTM** to capture contextual and sequential relationships between drug entities in a sentence. The model classifies interactions into multiple categories such as:

- Mechanism  
- Effect  
- Advice  
- Int  
- False (No Interaction)  

---

## Features

- Biomedical text preprocessing and entity tagging  
- Contextual embeddings using **BioBERT**  
- Sequential dependency learning with **BiLSTM**  
- Novel enhancements including:
  - **LoRA (Low-Rank Adaptation)** for efficient fine-tuning  
  - **BiGRU-based lightweight alternatives**  
  - **Attention Mechanisms** for improved token focus  
- Performance evaluation using:
  - F1-Macro  
  - Weighted F1 Score  
  - Precision  
  - Recall  

---

## Tech Stack

- Python  
- PyTorch  
- Hugging Face Transformers  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  

---

## Project Workflow

1. Data Collection from Biomedical Text Corpus  
2. XML Parsing and Sentence Extraction  
3. Drug Entity Tagging (`<e1>`, `<e2>`)  
4. Tokenization using BioBERT Tokenizer  
5. Model Training using R-BioBERT + BiLSTM  
6. Performance Evaluation  
7. Comparison with Proposed Contributions  

---

## Applications

- Clinical Decision Support Systems  
- Pharmacovigilance  
- Healthcare AI Solutions  
- Biomedical Literature Mining  
- Drug Safety Monitoring  

---

## Results

This project demonstrates how transformer-based biomedical NLP models can improve drug safety analysis by automatically extracting hidden interactions from medical text.

---

## Future Improvements

- Use larger biomedical models like PubMedBERT / BioLinkBERT  
- Multi-sentence context understanding  
- Graph Neural Networks for interaction modeling  
- Deployment as REST API for hospitals and healthcare systems  

---

## Author

**Haresh Kanaa**  
M.Tech Data Science  
Amrita Vishwa Vidyapeetham, Coimbatore

---
