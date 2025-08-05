# 🧹 Pre-processing for Farsi Texts
This repository provides a collection of text preprocessing notebooks specifically designed for Persian (Farsi) language content, such as tweets, articles, or user-generated text. These scripts help clean, normalize, and tokenize your raw data for further analysis or modeling.

# 📁 Repository Structure
| File / Notebook                           | Description                                                                |
| ----------------------------------------- | -------------------------------------------------------------------------- |
| `Cleaning_Tweets_of_URLs.ipynb`           | Removes URLs from Persian tweets                                           |
| `Convert_Informal_to_Formal.ipynb`        | Converts informal Persian words to formal equivalents                      |
| `Correct_Arabic_letters.ipynb`            | Fixes Arabic characters (e.g., replacing Arabic ی and ك with Persian ones) |
| `Delete_duplicate_and_empty_tweets.ipynb` | Removes empty or duplicate tweets                                          |
| `Delete_the_emojis.ipynb`                 | Strips emojis from text                                                    |
| `Remove_numbers.ipynb`                    | Deletes Persian, Arabic, and English numbers                               |
| `Remove_stop_words.ipynb`                 | Removes Persian stopwords                                                  |
| `Tokenized.ipynb`                         | Tokenizes Persian sentences into words                                     |
| `Hashtags.ipynb`                          | Extracts or removes hashtags from Persian tweets                           |
| `Prompt.txt`                              | Contains example prompts or raw input text                                 |


# ⚙️ How to Use
Upload your raw Farsi text data.

Run the notebooks in the recommended order (starting with cleaning and ending with tokenization).

If needed, manually review outputs or integrate with downstream NLP pipelines (e.g., topic modeling or sentiment analysis).

Note: There's no official library for converting Persian informal text to formal. However, this repo includes a custom script for it (Convert_Informal_to_Formal.ipynb). After preparing your .txt files, use Grok or any tokenizer and continue with the notebooks.

# 📦 Dependencies
Python (3.9+)

re, hazm, emoji, string, nltk

Compatible with Google Colab

# 👤 Author
Mona Faghfouri Azar
Data Analyst | NLP Researcher
GitHub: @MonaFaghfouri


