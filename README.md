# HumanText-vs-AIText

This project analyzes the **perplexity scores** of texts written by humans and texts generated by AI models (using **GPT-2**), exploring how human and AI-authored content can be distinguished based on this metric. The analysis includes comparisons between purely AI-generated text, AI-generated text that has been edited by humans, and purely human-written text.

## Data
https://www.kaggle.com/datasets/nguyentuannguyen/gpt-wiki-intro

## Visuals

Perplexity comparisons between **AI**-generated text, **human-edited AI** text, and **human** text: 

![Perplexity Histogram](https://github.com/user-attachments/assets/0f4c479a-2910-43b4-9c00-86289911cd2c)

![Perplexity Distribution](https://github.com/user-attachments/assets/28675e2b-a88f-4cea-958b-469c33346e74)

## References

- **Hugging Face Perplexity Documentation**: https://huggingface.co/docs/transformers/perplexity

- **DetectGPT: Zero-Shot Machine-Generated Text Detection using Probability Curvature**  
  [DetectGPT GitHub Repository](https://github.com/BurhanUlTayyab/DetectGPT)  
  [DetectGPT Paper on arXiv](https://arxiv.org/abs/2301.11305)  
  ```bibtex
  @misc{mitchell2023detectgpt,
      url = {https://arxiv.org/abs/2301.11305},
      author = {Mitchell, Eric and Lee, Yoonho and Khazatsky, Alexander and Manning, Christopher D. and Finn, Chelsea},
      title = {DetectGPT: Zero-Shot Machine-Generated Text Detection using Probability Curvature},
      publisher = {arXiv},
      year = {2023},
  }
