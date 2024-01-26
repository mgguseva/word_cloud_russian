# Notebook for Creating a Word Cloud from Russian Text

This Jupyter Notebook is designed to create a Word Cloud from text in Russian. The process involves several key steps: reading the text from a file, preprocessing it (which includes lemmatization and the removal of stop words), and then visualizing the most frequently occurring words in a word cloud. 

## Steps:

1. **Reading the Text File**: The text is read from a provided file, which should contain your Russian text.

2. **Text Preprocessing**:
    - **Lemmatization**: Words are converted to their base or dictionary form.
    - **Stop Words Removal**: Commonly used words that do not contribute to the meaning of the text (like 'и', 'в', 'на') are removed. This can be customized as needed.

3. **Word Cloud Generation**: A visual representation of the most frequent words in the text is created. This helps in highlighting key themes or words in the text.

4. **Visualization**: Displaying the generated word cloud within the notebook.
5. **Generating a Picture**: PNG-format

## Requirements:

This notebook requires the installation of specific Python libraries such as `nltk`, `pymorphy2`, and `wordcloud`. Ensure these are installed before running the notebook.

