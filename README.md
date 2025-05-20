# VikingLLM Agriculture Synthetic Instruction Dataset 🇫🇮🇸🇪

This repository contains **multilingual synthetic instruction–response dataset** in **Finnish** and **Swedish** designed to fine-tune large language models (LLMs) like VikingLLM for agriculture-focused conversational AI systems.

## 🌾 Project Background

This dataset is part of a broader initiative to support ethical and effective LLM deployment in the agricultural sector under the [AGRIHUBI project](https://maaseutuverkosto.fi/en/agrihubi/). It has been created using **public and internal agricultural knowledge documents** sourced from Finnish institutions, with synthetic dialogues generated to simulate realistic farmer–AI or citizen–AI interactions.

## 📁 Dataset Overview

The dataset includes **13 batches** totaling **3,250 Finnish and 3,250 Swedish** instruction–response pairs. Each sample is structured in JSONL format:

```json
{
  "instruction": "Kosteikkoviljely – Mitkä ovat sen edut valuma-alueen hallinnassa?",
  "response": "Kosteikkoviljely vähentää ravinnekuormitusta ja sitoo hiiltä..."
}
```

Each instruction–response pair is:
- **Non-repetitive**
- **Domain-specific** (soil, climate adaptation, water management, biodiversity, digital safety, etc.)
- **Balanced across themes and language**
- **Suitable for supervised fine-tuning of LLMs**

## 📦 File Structure

```bash
├── batch1_synthetic_finnish.jsonl
├── batch1_synthetic_swedish.jsonl
├── ...
├── batch13_synthetic_finnish.jsonl
├── batch13_synthetic_swedish.jsonl
```

Each file contains exactly **250 samples**. 

## ✅ Use Cases

- Fine-tuning multilingual LLMs like **Viking LLM**, **LLaMA**, **Mistral**, etc.
- Research in **instruction tuning**, **RAG (retrieval-augmented generation)**, and **AI ethics** in agriculture.
- Simulating human–AI interaction for Finnish and Swedish rural advisory contexts.

## 📜 License

This dataset is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** License.

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

**With attribution** to:
```
AGRIHUBI Project – Tampere University & partners
https://maaseutuverkosto.fi/en/agrihubi/
```

## 🙏 Acknowledgements

This dataset was generated using document material from:
- Natural Resources Institute Finland (LUKE)
- Finnish Environment Institute (SYKE)
- Universities and AMKs (HAMK, JAMK, Savonia, etc.)
- Public datasets related to Finnish agriculture and sustainability

Synthetic generation was guided by Finnish and Swedish language experts and LLM-based augmentation tools.

## 🧾 Citation

If you use this dataset in your research, please cite it as:

```
Khan, A. (2025). VikingLLM Agriculture Synthetic Instruction Dataset. AGRIHUB Project, Tampere University. https://github.com/GPT-Laboratory/finnish-swedish-agriculture-instruction-response
```

---

*For questions, feedback, or collaboration inquiries, please open an issue or contact [ayman.khan@tuni.fi](mailto:ayman.khan@tuni.fi).*