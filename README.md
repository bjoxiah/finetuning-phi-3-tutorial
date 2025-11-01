# 🤖 Fine-tune Phi-3 on Custom Data

Complete guide to fine-tuning Microsoft's Phi-3 on your own data and deploying to production.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1iJM8wDK5SG2FC7Shz6FxsLKu_QYi3nKw?usp=sharing)
[![YouTube](https://img.shields.io/badge/YouTube-Tutorial-red)](your-youtube-link)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

![Demo](assets/demo.gif)

## 🚀 Quick Start

### Google Colab (Recommended)
Click the badge above to open in Colab and run cell-by-cell.


## 🎥 Video Tutorial

Watch the complete walkthrough: [YouTube Link](your-link)

Timestamps:
- 00:00 - Introduction
- 02:30 - Setup & Data Prep
- 08:00 - Fine-tuning
- 18:00 - Deployment

## 📁 Repository Structure

- `notebooks/`: Interactive Jupyter/Colab notebooks
- `data/`: Sample dataset


## 📊 Data Format

Your training data should be in JSONL format:
```json
{
  "messages": [
    {"role": "system", "content": "You are a helpful assistant."},
    {"role": "user", "content": "What is X?"},
    {"role": "assistant", "content": "X is..."}
  ]
}
```

See [data/sample_training_data.jsonl](data/sample_training_data.jsonl) for examples.


## 🤝 Contributing

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

## 📝 License

MIT License - see [LICENSE](LICENSE)