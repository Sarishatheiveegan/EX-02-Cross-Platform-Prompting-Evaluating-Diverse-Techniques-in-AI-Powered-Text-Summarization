# EX-02: Cross-Platform Prompting - Evaluating Diverse Techniques in AI-Powered Text Summarization
### MARINO SARISHA T
### 212223240084
## AIM
To evaluate and compare the effectiveness of different prompting techniques (zero-shot, few-shot, chain-of-thought, and role-based) across multiple AI platforms (ChatGPT, Gemini, Claude, and Copilot) for the specific task of **text summarization**.

---

## ALGORITHM

1. **Define the Use Case**
   - Task chosen: Text summarization of a medium-length technical article.
   - Goal: Evaluate each platform’s ability to condense information while retaining accuracy, coherence, and context.

2. **Create a Set of Prompts**
   - **Zero-shot prompt:** “Summarize the following article in 100 words.”
   - **Few-shot prompt:** Provide 2–3 examples of good summaries before the main text.
   - **Chain-of-thought prompt:** “Summarize the article step-by-step by first identifying key points and then combining them.”
   - **Role-based prompt:** “Act as a professional content curator. Write a precise summary suitable for a technical report.”

3. **Run the Experiment on Each Platform**
   - Tested on **ChatGPT**, **Gemini**, **Claude**, and **Copilot**.
   - Used identical prompts and similar input formats.
   - Recorded:
     - Response clarity
     - Output time
     - Ease of interaction
     - Any inconsistencies or technical issues

4. **Evaluate Response Quality**
   - **Accuracy:** Faithfulness to source content.
   - **Clarity:** How easy it is to understand the summary.
   - **Depth:** Inclusion of main ideas and logical flow.
   - **Relevance:** Avoidance of unrelated or missing points.

5. **Compare Performance**
   - Compared based on the criteria above.
   - Observed which prompting technique produced the best results for each platform.

---

## COMPARISON TABLE

| Platform | Prompt Type | Accuracy | Clarity | Depth | Relevance | Observations |
|-----------|--------------|-----------|----------|--------|------------|---------------|
| **ChatGPT** | Chain-of-thought | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐⭐ | Very coherent summaries with contextual understanding. Excellent balance of depth and brevity. |
| **Gemini** | Few-shot | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐☆ | Clear summaries, slightly generic phrasing, performs well with examples. |
| **Claude** | Role-based | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐☆ | Professional tone, maintains context, slightly verbose at times. |
| **Copilot** | Zero-shot | ⭐⭐⭐☆ | ⭐⭐⭐☆ | ⭐⭐☆ | ⭐⭐⭐ | Quick but lacks nuance; suitable for short summaries or coding-related text. |

<img width="1064" height="399" alt="Screenshot 2025-12-04 104428" src="https://github.com/user-attachments/assets/791e9681-3182-45bb-a6e5-2c6a9daafe16" />

---

## RESULTS AND DISCUSSION

- **Best Performer:** **ChatGPT (Chain-of-Thought Prompting)** produced the most detailed and contextually rich summaries.
- **Gemini** performed consistently well with few-shot prompts, showing improvement when given examples.
- **Claude** delivered formal, well-structured summaries but slightly exceeded word limits.
- **Copilot** was fast but less suitable for nuanced summarization tasks; better for concise or technical content.

**Prompting Insights:**
- Chain-of-thought prompting improved comprehension and logical sequencing.
- Few-shot prompting enhanced structure and tone consistency.
- Role-based prompting ensured domain-specific vocabulary.
- Zero-shot prompting worked best for brief and general summaries.

---

## CONCLUSION

This experiment demonstrates that **prompt engineering significantly influences the quality of AI-generated summaries**.  

- **ChatGPT** with **chain-of-thought prompting** is ideal for detailed, high-quality summarization.
- **Gemini** and **Claude** also deliver strong performance, especially with role-based or few-shot techniques.
- **Copilot** is best suited for short, factual, or code-related summaries rather than narrative content.

**Recommendation:**  
For academic or professional use, adopt **ChatGPT or Claude** with **chain-of-thought** or **role-based** prompting for the most coherent and contextually accurate results.

---

## OUTPUT SCREENSHOTS
<img width="539" height="365" alt="Screenshot 2025-12-04 104310" src="https://github.com/user-attachments/assets/1ac1605f-1a1a-4a62-8ad6-a88a18e861c2" />


---

## RESULT
Thus, the effectiveness of various prompting techniques across multiple AI platforms was successfully evaluated for the task of text summarization.
