# 🤖 HSE Student Assistant Bot

An intelligent Telegram bot designed to answer Frequently Asked Questions (FAQ) from students and professors at HSE University.

## 🔧 Features
* **Hybrid Search Engine:** Combines **TF-IDF** and **Word2Vec** to find the most relevant answers.
* **Best Match Selection:** Uses **Cosine Similarity** to rank answers and dynamically selects the best response between the two algorithms.
* **Asynchronous Interface:** Built with `aiogram` for fast and non-blocking user interaction.

## 🛠 Tech Stack
* Python
* Aiogram (Telegram Bot API)
* Scikit-learn (TF-IDF, Cosine Similarity)
* Gensim (Word2Vec)
* NumPy
