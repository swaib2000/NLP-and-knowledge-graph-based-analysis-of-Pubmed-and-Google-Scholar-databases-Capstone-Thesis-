# NLP and Knowledge Graph-based Analysis of PubMed and Google Scholar Databases

This repository contains the code, notebooks, and analysis developed as part of the **M.Tech Capstone Project (IIIT Delhi)** titled:

> **“NLP and Knowledge Graph-based Analysis of PubMed and Google Scholar Databases”**

The project focuses on large-scale **biomedical text mining**, **named entity recognition (NER)**, **interaction extraction**, and **dynamic knowledge graph construction** from PubMed literature, with a case study on **Parkinson’s Disease**.

---

## 🔍 Project Overview

Biomedical literature contains rich information about **genes, chemicals, diseases, proteins, and pathways**, but extracting structured knowledge at scale is challenging.

This project:
- Scrapes and processes **PubMed abstracts** over multiple decades
- Applies **NLP and biomedical NER** using Flair, SciSpacy, and PubTator
- Extracts **entity–entity interactions** (e.g., gene–chemical regulation)
- Builds **dynamic knowledge graphs**
- Visualizes interactions through **interactive notebooks and Streamlit-style workflows**

The final outcome is a **structured, explorable molecular interaction graph** derived entirely from unstructured scientific text.

---

## 🧠 Key Features

- Automated PubMed abstract retrieval
- Biomedical Named Entity Recognition (NER)
- Extraction of:
  - Genes
  - Chemicals / Drugs
  - Diseases
  - Proteins
  - Brain regions & PET tracers
- Interaction & regulation identification (activation, inhibition, etc.)
- Statistical analysis of entity frequencies
- Dynamic and interactive knowledge graph visualization

---

## 📁 Repository Structure

```text
├── pubmedmine_R.ipynb
│   └── R-based PubMed text mining using pubmed.mineR
│       (entity extraction, sentence context, interaction mining)
│
├── Interaction.ipynb
│   └── Identification and classification of interactions between
│       genes, chemicals, diseases, and pathways
│
├── Dynamic_Map.ipynb
│   └── Construction and visualization of dynamic knowledge graphs
│       showing interaction–regulation relationships
│
├── Group_28_Final Capstone Report.pdf
│   └── Detailed project report describing methodology, experiments,
│       results, visualizations, and conclusions
