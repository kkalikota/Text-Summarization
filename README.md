# Text-Summarization
<img src = "https://github.com/user-attachments/assets/f3473666-f50a-4562-a7ef-5a9779096f05">

### Overview:
The text summarization project focused on extracting key information from large texts by creating concise summaries. The goal was to identify the most relevant sentences using a word frequency-based approach.

### Approach:
- **Preprocessing**: Used the spaCy library to clean and preprocess the text (tokenization, lemmatization, stopword removal).
- **Word Frequency**: Calculated the frequency of words in the document.
- **Sentence Scoring**: Scored each sentence based on the frequency of important words it contained.
- **Summarization**: Selected top-scoring sentences to generate the summary.

### Impact:
This approach significantly reduced the text length while maintaining the key points, providing a quick way to grasp essential information from long documents.

### Conclusion:
By leveraging spaCy for preprocessing and a simple word frequency-based scoring method, the project effectively produced relevant and concise summaries with minimal computational resources.
