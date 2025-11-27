# AD331-Prompt-Engineering-AsmaBegum

# Prompt Engineering for Performance Improvement  
**Author:** Asma Begum  
**Course:** AD331 – Fall 2025  

---

##  Overview
This project demonstrates the impact of prompt engineering on Large Language Model (LLM) performance.  
The task selected for this assignment is **structured data extraction** from an unstructured product review.  
This requires reasoning, attention to detail, entity recognition, and strict output formatting — making it an ideal candidate for testing multiple prompt engineering strategies.

The experiment includes:
1. A baseline prompt  
2. Three distinct prompt engineering techniques:
   - Role Prompting  
   - JSON Output Formatting  
   - Chain-of-Thought (CoT) Reasoning  
3. A final optimized prompt combining the most successful techniques  
4. A qualitative evaluation of each output

All prompts, outputs, and analysis are documented in the Jupyter Notebook included in this repository.

---

## Task Description
**Goal:** Extract structured information from a messy product review.

**Fields to extract:**
- product  
- price  
- reviewer  
- date  
- sentiment  
- summary  

This task challenges the LLM in both reasoning and format consistency.

---

## Constant Input 
The following review text was used as the constant input throughout the experiment:

