# Private Credit Index Construction from SEC iXBRL Filings

(CFEM Team: Abhinav Chhabra, Ananya Bajaj, Chia-Yi Chien, Masis Akdemir, Mohamed Azahriou)

## Overview
This project builds a **loan-level private credit index** using **SEC iXBRL filings from Business Development Companies (BDCs)**, designed to replicate and extend the **Cliffwater Direct Lending Index (CDLI)**. The goal is to transform fragmented, unstructured regulatory disclosures into a **clean, standardized, and analysis-ready dataset** for private credit research.

## Motivation
Private credit benchmarks are typically **paywalled, opaque, and unavailable at the loan level**. This project demonstrates how public regulatory filings can be engineered into a transparent index that enables **return attribution, risk analysis, and early-warning signal detection**.

## Key Features
- **Automated ETL pipeline** to parse, clean, and standardize heterogeneous SEC iXBRL filings  
- ~**300K loan-level observations across 176 BDCs** from 2023-25
- **Position-level return reconstruction** with decomposition into:
  - Cash interest income  
  - PIK income  
  - Price returns  
- **Market-value weighted index construction**, achieving:
  - **86.95% correlation** and **0.33% tracking error** vs. CDLI
- **LLM-based enrichment** of sparse and unstructured disclosure fields
- Construction of **sub-indices**:
  - By loan seniority (matching CDLI-S with ~87% correlation)
  - By sector (Technology, Healthcare, Finance & Insurance)

## Applications
- Return attribution and income vs. price decomposition  
- Credit risk and covenant deterioration analysis  
- Early-warning signals (demonstrated via a **First Brands Group bankruptcy case study**)  
- Transparent private credit benchmarking and research

## Skills & Tools
- SEC iXBRL Parsing  
- Automated ETL Pipelines  
- Data Engineering  
- Private Credit Index Construction  
- Benchmark Replication (CDLI)  
- Market-Value Weighting  
- Return Reconstruction & Desmoothing  
- LLM-Based Financial Data Extraction
