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

So I grabbed this “XJ200 blender” last week on Amazon on July 8th — think it was around 79 dollars but not sure if it was on sale.
Anyway, Maria L. here. Honestly, kinda disappointed. Works OK but the motor smells funny sometimes. I'd rate it 3 out of 5.


This text is saved in `raw_input.txt`.

---

## Prompt Experiments

Five prompts were tested:

1. **Baseline Prompt**  
2. **Technique 1 – Role Prompting**  
3. **Technique 2 – JSON Output Formatting**  
4. **Technique 3 – Chain-of-Thought Reasoning**  
5. **Final Optimized Prompt**

All prompt texts and outputs are documented in the notebook:  
`assignment_prompt_engineering.ipynb`

---

## Results Summary Table

| Prompt Type | Accuracy | Format | Completeness | Notes |
|------------|----------|--------|--------------|-------|
| Baseline Prompt | 2/10 | 1/10 | 2/10 | Very incomplete; no structure |
| Technique 1: Role Prompting | 6/10 | 4/10 | 7/10 | More detail, still unstructured |
| Technique 2: JSON Formatting | 8/10 | 10/10 | 8/10 | Clean JSON; shallow reasoning |
| Technique 3: Chain-of-Thought | 9/10 | 10/10 | 9/10 | Improved accuracy and reasoning |
| **Final Optimized Prompt** | **10/10** | **10/10** | **10/10** | Best structured and most accurate output |

---

## Key Lessons Learned

- **Role prompting helps the model act like a specialist**, improving extraction quality.  
- **JSON formatting instructions enforce consistent structure** and reduce errors.  
- **Chain-of-thought reasoning greatly improves accuracy** in multi-step tasks.  
- **The final optimized prompt combining all techniques delivered the best performance** across every metric.  
- Prompt engineering plays a critical role in improving LLM reliability.

---

---

## Video Demonstration 

A video accompanies this assignment and includes:

- Introduction to the task  
- Baseline prompt and its poor performance  
- Technique 1: Role Prompting  
- Technique 2: JSON Formatting  
- Technique 3: Chain-of-Thought  
- Final optimized prompt  
- Comparison and explanation of why each technique improved the results  

The video shows both **my face** and **my screen** as required.

*(A YouTube link will be submitted on Canvas.)*

---
## End of README

All components required by the assignment are included:
- Baseline prompt  
- Three advanced prompt engineering techniques  
- Final optimized prompt  
- Qualitative evaluation  
- Summary table  
- Notebook  
- README  
- Video demonstration  



## Repository Contents


