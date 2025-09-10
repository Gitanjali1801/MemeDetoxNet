# MemeDetoxNet : **Balancing Toxicity Reduction and Context Preservation in Memes**

MemeDetoxNet is a modular framework designed to detect and detoxify harmful memes by leveraging multimodal deep learning techniques. It combines CLIP-based interpretability with large language models (LLMs) to identify and transform toxic visual and textual elements.

## 🔍 Key Features
- **Toxicity Detection**: Classifies memes based on ethical content.
- **Visual & Textual Localization**: Highlights offensive regions and phrases.
- **Content Detoxification**: Replaces toxic text and blurs harmful visuals to generate morally acceptable alternatives.

## 📁 Repository Structure
- `classifierfor_ethic.ipynb`: Meme classification based on ethical attributes.
- `finetuning.ipynb`: Fine-tuning pre-trained models for toxicity detection.
- `inference.py`: Inference pipeline for meme detoxification.
- `inferencing.ipynb`: Variant inference with additional filters.
- `llm.ipynb`: Text detoxification using large language models.
- `replacewords.ipynb`: Word-level replacement strategies for offensive text.

## 📖 Reference
If you use this paper, please cite:

```bibtex
@inproceedings{kumari-etal-2025-memedetoxnet,
  title = "{M}eme{D}etox{N}et: Balancing Toxicity Reduction and Context Preservation",
  author = "Kumari, Gitanjali and Solanki, Jitendra and Ekbal, Asif",
  booktitle = "Findings of the Association for Computational Linguistics: ACL 2025",
  year = "2025",
  address = "Vienna, Austria",
  publisher = "Association for Computational Linguistics",
  url = "https://aclanthology.org/2025.findings-acl.1286/",
  doi = "10.18653/v1/2025.findings-acl.1286"
}
