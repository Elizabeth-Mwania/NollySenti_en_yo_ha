# NollySenti: Multilingual Sentiment Analysis for Nollywood Films

A comprehensive sentiment analysis project exploring emotional patterns in Nigerian cinema across multiple languages (English, Yoruba, and Hausa).

## 📋 Overview

**NollySenti_en_yo_ha** is a machine learning project dedicated to analyzing and classifying sentiment in Nollywood (Nigerian film industry) content. This project leverages multilingual NLP techniques to understand audience sentiment across three major Nigerian languages: English, Yoruba, and Hausa.

### Key Features

- **Multilingual Support**: Sentiment analysis in English, Yoruba, and Hausa
- **Nollywood Focus**: Specifically trained on Nigerian film industry content
- **Comprehensive Dataset**: Includes training, development, and test datasets
- **GPU-Optimized**: Runs on Google Colab with T4 GPU acceleration
- **Deep Learning Approach**: Implements transformer-based models for accurate sentiment classification

## 📊 Project Structure

```
NollySenti_en_yo_ha/
├── NollySenti_en_yo_ha.ipynb    # Main analysis notebook
└── README.md                      # Project documentation
```

## 🗂️ Datasets

The project utilizes TSV-formatted datasets for training and evaluation:

- **train.tsv**: Training dataset for model development
- **dev.tsv**: Development/validation dataset for hyperparameter tuning
- **test.tsv**: Test dataset for final model evaluation

Each dataset contains labeled examples of film-related text with corresponding sentiment labels.

### Dataset Source

- **Primary Dataset**: [Davlan/nollysenti](https://huggingface.co/datasets/Davlan/nollysenti) - A comprehensive multilingual Nollywood sentiment analysis dataset available on Hugging Face

## 🛠️ Technical Stack

- **Language**: Python 3
- **Deep Learning Framework**: PyTorch / Transformers
- **Computation**: GPU-accelerated (T4 GPU on Google Colab)
- **Notebooks**: Jupyter Notebook (IPython)
- **Data Format**: TSV (Tab-Separated Values)

### Pre-trained Models

- **Model**: [Davlan/afro-xlmr-base](https://huggingface.co/Davlan/afro-xlmr-base) - XLM-RoBERTa model fine-tuned for African languages including Yoruba and Hausa

## 🚀 Getting Started

### Prerequisites

- Google Colab account (recommended) or local Python environment
- GPU support (T4 or equivalent) for optimal performance
- Required Python packages (automatically installed in notebook)

### Usage

1. **Open the notebook** in Google Colab:
   - Upload `NollySenti_en_yo_ha.ipynb` to your Colab workspace
   - Enable GPU acceleration: Runtime → Change runtime type → GPU

2. **Run the cells** sequentially to:
   - Load and explore the multilingual datasets
   - Preprocess text data
   - Train sentiment classification models
   - Evaluate model performance
   - Generate sentiment predictions

3. **Customize analysis** by modifying parameters:
   - Language focus
   - Model architecture
   - Training hyperparameters
   - Dataset sampling

## 📈 Methodology

The project follows a standard NLP pipeline:

1. **Data Loading**: Import TSV datasets into pandas DataFrames
2. **Preprocessing**: Text cleaning and tokenization
3. **Feature Engineering**: Language-specific embeddings and representations
4. **Model Training**: Train transformer-based classifiers
5. **Evaluation**: Assess accuracy, precision, recall, and F1-score
6. **Inference**: Classify sentiment for new film-related text

## 🎯 Use Cases

- Analyze audience reactions to Nollywood films
- Understand sentiment patterns across different Nigerian languages
- Build recommendation systems based on audience sentiment
- Study cultural and linguistic variations in sentiment expression
- Support content creators in understanding audience feedback

## 📚 Datasets Format

The TSV files contain the following structure:
- **Column 1**: Text/Review content
- **Column 2**: Sentiment label (typically: positive, negative, neutral)

Example:
```
This movie was absolutely amazing!	positive
I didn't enjoy it much	negative
It was okay	neutral
```

## 🔍 Key Insights

Through this analysis, we can uncover:
- Language-specific sentiment patterns
- Cultural nuances in film appreciation
- Sentiment distribution across film categories
- Linguistic features that indicate sentiment

## 🤝 Contributing

Contributions are welcome! Consider:
- Expanding the dataset with additional languages
- Implementing additional sentiment classification models
- Improving multilingual preprocessing techniques
- Adding visualization and analysis tools
- Creating language-specific evaluation metrics

## 📝 License

This project is open source and available for educational and research purposes.

## 👤 Author

**Elizabeth Mwania**  
[GitHub Profile](https://github.com/Elizabeth-Mwania)

## 📞 Contact & Support

For questions or suggestions regarding this project, please open an issue on this repository.

---

## 📚 References & Resources

### Dataset & Model Resources

- **Dataset**: [Davlan/nollysenti](https://huggingface.co/datasets/Davlan/nollysenti) - Multilingual Nollywood sentiment analysis dataset on Hugging Face
- **Pre-trained Model**: [Davlan/afro-xlmr-base](https://huggingface.co/Davlan/afro-xlmr-base) - XLM-RoBERTa model fine-tuned for African languages

### Academic References

- **Paper**: [NollySenti: Sentiment Analysis for Code-Switched Nollywood Movie Reviews](https://arxiv.org/abs/2305.10971)
- **Original Implementation**: [IyanuSh/NollySenti - GitHub Repository](https://github.com/IyanuSh/NollySenti)

### Documentation & Tutorials

- [Transformers Library Documentation](https://huggingface.co/transformers/)
- [Nollywood Industry Overview](https://en.wikipedia.org/wiki/Nollywood)
- [Multilingual NLP Best Practices](https://huggingface.co/docs/transformers/multilingual)
- [Sentiment Analysis Tutorials](https://huggingface.co/course)

---

**Last Updated**: June 2026
