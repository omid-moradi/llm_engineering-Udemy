# LLM Engineering - Master AI and LLMs

## My journey through Ed Donner’s Udemy course using LLaMA 3.2-1B Instruct

![lama](LLM%20UDEMY/image/lama.png)

This repository contains all Jupyter notebooks and hands-on exercises from the **LLM Engineering** course by Ed Donner on Udemy. I have implemented and executed the entire course using the **LLaMA 3.2-1B Instruct** model via **Hugging Face**, ensuring full compatibility with both local and Colab environments.

The projects build progressively, covering key concepts such as prompt engineering, LLM evaluation, fine-tuning basics, and agent-based AI. While the course may reference different models (e.g., GPT-4o), I exclusively used LLaMA 3.2-1B Instruct to demonstrate that powerful results are achievable even with lightweight open-source models.

---

### Before You Begin

All notebooks here were tested and run using:
- **LLaMA 3.2-1B Instruct** via **Hugging Face Transformers and PEFT**
- **Google Colab** for GPU-based execution when needed

You may also choose to run the same notebooks using other tools like **Ollama** locally or **API-based alternatives** depending on your setup. However, the implementation in this repo is based entirely on Hugging Face tools.

---

### Getting Started (Recommended)
1. Set up a Python environment (locally or in Colab)
2. Install necessary packages: `transformers`, `accelerate`, `peft`, and `datasets`
3. Load the model: `meta-llama/Llama-3.2-1B-Instruct` from Hugging Face
4. Run any of the provided notebooks for that week's topic

> ⚠️ **Note:** Avoid using heavier models like `llama3.3` unless you have sufficient resources (e.g., 70B+ parameters require substantial GPU power).

---

### Repository Structure
This repo is organized by week, as per the course structure:
- **Week 1 to Week 8**: Thematic learning with increasing difficulty
- Projects include summarization, RAG, agentic systems, tokenizer analysis, and more
- All solutions adapted for LLaMA 3.2-1B using Hugging Face

### Want to Explore?
Feel free to modify, extend, or run these notebooks. The best learning happens through experimentation. You’re welcome to submit pull requests if you’ve built alternative solutions using LLaMA 3.2.

---

### Acknowledgment
All course content and original idea credits go to **Ed Donner**. This implementation reflects my own learning experience, tailored for Hugging Face-based execution of open-source LLMs.

> For more info about the course and slides: [Ed Donner's LLM Resources](https://edwarddonner.com/2024/11/13/llm-engineering-resources/)

---

Let’s build cool things with LLMs 🚀