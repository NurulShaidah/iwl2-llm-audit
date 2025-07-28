# 🔍 IWL2 Team Project: Smart Contract Vulnerability Auditing using LLMs

This repository contains the code deliverables and notebooks for our IWL2 team project, focused on auditing Solidity smart contracts for vulnerabilities using Large Language Models (LLMs).

---

## 📁 Project Structure

- **Gemini_Audit.ipynb**  
  Uses Gemini LLM to audit smart contracts based on CVE data and CFG analysis.

- **OpenAI_Audit.ipynb**  
  Uses OpenAI GPT-4 to audit smart contracts with the same configuration and logic as the Gemini pipeline.

- **Comparison_and_Graphs.ipynb**  
  Compares outputs from both LLMs, including accuracy, precision, recall, and severity plots.

- **cve_data.json**  
  Known smart contract vulnerabilities with metadata and code samples.

- **ContractBenchmark.csv**  
  Benchmark dataset for comparing LLM audit results against ground truth.

- **TrainingContracts.json**  
  Training examples used in Retrieval-Augmented Generation (RAG) prompts.

---

## 🚀 How to Use

1. Open the Colab notebooks using the links below or directly from this repo.
2. Follow the cell execution steps inside each notebook.
3. Ensure the necessary files (e.g., `cve_data.json`, `ContractBenchmark.csv`) are uploaded in the Colab environment before running.

---

## 🔗 Colab Notebooks

- **Gemini LLM Audit**  
  https://colab.research.google.com/drive/1dI9b0MRkYscpDHZyK5t4wIVlSuB9hCJ5?usp=sharing

- **OpenAI LLM Audit**  
  https://colab.research.google.com/drive/1vmRmNfs-O0hnyHUUaDLTO06dYtt9Lf7j?usp=sharing

- **Comparison and Graphs**  
  https://colab.research.google.com/drive/12zJlyXZDdVdhdEBqLa5zyAUukmP4NGu?usp=sharing

---

## 👥 Team Members

- Nurul Shaidah  
- Nur Afiqah Binte Omar  
- Manesh Kaliannan  
- Varsha Kulkarni
