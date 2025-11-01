# 🤖 Fine-Tune Phi-3 on Custom Data

Complete guide to fine-tuning Microsoft's Phi-3 on your own data and deploying to production.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1iJM8wDK5SG2FC7Shz6FxsLKu_QYi3nKw?usp=sharing)
[![YouTube](https://img.shields.io/badge/YouTube-Tutorial-red)](https://youtu.be/He-vkp1qUzU)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 🚀 Quick Start

### Google Colab (Recommended)
Click the badge above to open in Colab and run cell-by-cell.


## 🎥 Video Tutorial

Watch the complete walkthrough: [YouTube Link](https://youtu.be/He-vkp1qUzU)

Timestamps:
- 00:00 - Intro  
- 00:59 - Fine-Tuning Processes  
- 03:20 - Colab Code Review  
- 15:14 - Conclusion  

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

See [data/sample_training_data.jsonl](data/training_set_converted.jsonl) for examples.


## 🤝 Contributing

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

## 📝 License

MIT License - see [LICENSE](LICENSE)
