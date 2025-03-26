# **Spelling and Grammar Corrector Chatbot**
This project is a chatbot that helps users correct spelling and grammar errors in their text. The bot can process both individual sentences and entire text documents. It uses Natural Language Processing (NLP) techniques to correct typos, fix grammar issues, and even recognize entities like names, cities, and other important terms. The bot operates in two modes:
1. Phrase Mode: Users can input a single sentence or phrase, and the bot will
correct any spelling or grammar issues.
2. Document Mode: Users can provide a path to a text document, and the bot will process the content to detect and correct errors.

[Video demo](https://www.youtube.com/watch?v=IxSSh_URLeE)

## Key Features:
- Spelling correction using TextBlob.
- Grammar checking with LanguageTool.
- Entity recognition (names, cities, etc.) using spaCy.
- Text processing in both phrase and document modes.
- The program terminates when the user types "exit".

Tech Stack:
- Python (for the core programming)
- TextBlob (for spelling correction)
- LanguageTool-Python (for grammar checking)
- spaCy (for entity recognition)
---

## Setup 🛠️

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mohamedtaqysalmi/Applied-NLP-Chatbots-Projects.git
   cd SpellFixer-Bot
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook SpellFixer-Bot.ipynb
   ```

## File Structure 📂
```
SpellFixer-Bot/
├── SpellFixer-bot.ipynb  # Main notebook
├── requirements.txt                 # Dependencies
└── README.md
```

## Dependencies 📦
Listed in `requirements.txt`:
```
pandas>=1.3.0
numpy>=1.21.0
scikit-learn>=1.0.0
textblob>=0.15.3
language-tool-python>=2.7.0
spacy>=3.0.0
```

## License 📜
MIT License. 

---

**Author**: [Mohamed-Taqy Salmi](https://linkedin.com/in/mohamedtaqysalmi)  
**Contribute**: PRs and issues welcome!  
```
