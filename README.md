# Research Project: Development of Abstractive Text Summarization Model Based on BiLSTM and Attention Mechanism

## Overview
This research aims to develop an abstractive text summarization model based on BiLSTM with an attention mechanism, focusing on the Mahabharata stories in Javanese. The study explores how abstractive summarization models can be adapted for the Javanese language, considering the linguistic and cultural aspects of the Mahabharata stories. As an innovation, this research employs a hybrid approach based on BiLSTM and attention to align with the characteristics of the Mahabharata stories.

The results of this research are expected to contribute to automatic summarization technology, particularly for the Javanese language, and provide solutions that are academically and practically relevant.

## Metadata
- **Model**: BiLSTM + Attention Mechanism
- **Dataset Focus**: Mahabharata stories in Javanese
- **Evaluation Method**: ROUGE (Recall-Oriented Understudy for Gisting Evaluation)
- **Language**: Javanese
- **Data Source**: Website [sastra.org](https://sastra.org)
- **Output Dataset Format**: CSV

## Tools
- **Platform**: Google Colab
- **Programming Framework**: Python
- **Main Libraries**:
  - TensorFlow/Keras: For BiLSTM model development
  - NLTK/Spacy: For text preprocessing
  - BeautifulSoup: For web scraping the dataset
  - Pandas: For dataset management
  - ROUGE-metric library: For model performance evaluation
- **API**: ChatGPT (as an additional reference for summaries, limited to a maximum of 10% of the original text)

## Installation Guide
1. **Open Google Colab**:
   - Ensure you have a Google account to access Google Colab.

2. **Clone the Repository**:
   - Use the following command in one of the Google Colab cells:
     ```python
     !git clone <repository-url>
     %cd <repository-directory>
     ```

3. **Install Dependencies**:
   - Install the required libraries:
     ```python
     !pip install -r requirements.txt
     ```
