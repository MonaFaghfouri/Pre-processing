# 🧹 Pre-processing for Farsi Texts
This repository provides a collection of text preprocessing notebooks specifically designed for Persian (Farsi) language content — such as tweets, articles, and user-generated texts. These scripts help you clean, normalize, and tokenize raw text data for further NLP analysis or modeling tasks.

# 📁 Repository Structure
| File / Notebook                           | Description                                                                |
| ----------------------------------------- | -------------------------------------------------------------------------- |
| `Cleaning_Tweets_of_URLs.ipynb`           | Removes URLs from Persian tweets                                           |
| `Convert_Informal_to_Formal.ipynb`        | Converts informal Persian words to formal equivalents                      |
| `Converting_to_Normalized_Form.ipynb`     | Normalizes spacing, punctuation, diacritics, and standardizes the text     |
| `Correct_Arabic_letters.ipynb`            | Fixes Arabic characters (e.g., replacing Arabic ی and ك with Persian ones) |
| `Delete_duplicate_and_empty_tweets.ipynb` | Removes empty or duplicate tweets                                          |
| `Delete_the_emojis.ipynb`                 | Removes emojis from text                                                   |
| `Remove_numbers.ipynb`                    | Deletes Persian, Arabic, and English numbers                               |
| `Remove_stop_words.ipynb`                 | Removes common Persian stopwords                                           |
| `Tokenized.ipynb`                         | Tokenizes Persian sentences into words                                     |
| `Hashtags.ipynb`                          | Extracts or removes hashtags from Persian tweets                           |
| `Prompt.txt`                              | Contains example prompts or raw input text                                 |



# ⚙️ How to Use
Upload your raw Persian .txt or .csv files.

Run the notebooks in logical order starting from normalization and cleaning, and ending with tokenization.

Each notebook can be used independently, or integrated into a full NLP pipeline.

💡 For converting informal Persian to formal, use Convert_Informal_to_Formal.ipynb.
💡 To standardize spacing and remove diacritics, run Converting_to_Normalized_Form.ipynb.

# 📦 Dependencies
Python 3.9+

hazm – for Persian NLP

re, string, emoji, nltk, pandas

These notebooks are Colab-compatible and easy to run step-by-step.

# 👤 Author
Mona Faghfouri Azar
Data Analyst | NLP Researcher
GitHub: @MonaFaghfouri


