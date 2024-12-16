# Kinase Activity Inference Benchmark

This repository provides a comparative benchmark analysis of kinase activity inference tools: **Kinex**, **PhosX**, and **RoKAI**, using phosphoproteomics data.

## Overview  
Inference of kinase activity is critical for understanding cellular signaling pathways. This project evaluates the predictive precision and biological relevance of three tools Kinex, phosX, and roKAI based on SARS-CoV-2 phosphoproteomics data. 

## Directory Structure  
```plaintext
├── enrichment_analysis/    # Tables for chapter 3.4 with results from enrichr
├── initial_data/           # Raw phosphoproteomics data
├── Kinex/                  # Input/output tables and pics for Kinex tool
├── phosX/                  # Input/output tables and pics for PhosX tool
├── RoKAI/                  # Input/output tables and pics for RoKAI tool
├── mapping_seq_uniprot_for_phosX.csv  # Mapping file for PhosX input
├── util_scripts.ipynb      # Utility scripts for preprocessing, analysis, and plots


