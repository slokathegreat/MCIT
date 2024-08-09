### Task Overview: Developing a Question Answering Model

The goal of this project is to develop a robust question-answering model utilizing the ARCD dataset. The approach involves exploring and implementing multiple techniques to enhance the model's performance.

### Techniques Employed:

1. **Classical Machine Learning**  
   Initial efforts involve leveraging traditional machine learning methods to establish a baseline performance for the question-answering task.

2. **Fine-Tuning a Transformer**  
   Advanced techniques include fine-tuning a pre-trained transformer model, adapting it specifically to the nuances of the ARCD dataset for improved accuracy.

3. **Building a Retrieval-Augmented Generation (RAG) System**  
   The final phase focuses on constructing a Retrieval-Augmented Generation (RAG) system, which combines retrieval-based methods with generative models to provide more contextually accurate answers.
# Classical Machine Learning Approach for Question Answering (Accuarcy 72)

## Data Cleaning
- **Text Normalization**: Remove or standardize text elements such as punctuation and special characters.
- **Tokenization**: Split text into smaller units, such as words or phrases, to facilitate further analysis.
- **Stop Words Removal**: Eliminate common words (e.g., "هذا", "الذى") that don’t add significant meaning to the text.
- **Stemming/Lemmatization**: Reduce words to their base or root form (e.g., converting "يحب" to "حب") to treat different forms of a word as the same.

## TF-IDF Vectorization
- **Term Frequency-Inverse Document Frequency (TF-IDF)**: Convert text data into numerical features by evaluating the importance of words in the context of the entire dataset.
  - **Term Frequency (TF)**: Count the occurrences of each term in a document.
  - **Inverse Document Frequency (IDF)**: Assess the importance of a term by considering its frequency across all documents. Terms that appear frequently in many documents are given lower weights.


This classical approach provides a solid foundation and baseline performance, which can be further enhanced with more advanced techniques like fine-tuning transformers and developing Retrieval-Augmented Generation (RAG) systems.
