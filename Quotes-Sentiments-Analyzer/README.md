# Quotes Sentiment Analyzer 📊

A Python Jupyter Notebook that scrapes quotes from [quotes.toscrape.com](http://quotes.toscrape.com), analyzes their sentiment using TextBlob, and visualizes the results with Matplotlib/Seaborn. Includes an interactive search feature to explore quotes by author or keyword.

[Video demo](https://www.youtube.com/watch?v=rjdL_bfSNRI)

## Features ✨
- **Web Scraping**: Collect quotes, authors, and tags from multiple pages.
- **Sentiment Analysis**: Calculate polarity scores (positive/negative/neutral) for each quote.
- **Visualizations**:  
  - Number of quotes per author.  
  - Average sentiment per author.  
  - Sentiment distribution across quotes.  
- **Interactive Search**: Find quotes by author or keyword.

## Setup 🛠️

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mohamedtaqysalmi/quotes-sentiment-analyzer.git
   cd quotes-sentiment-analyzer
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook Quotes_Sentiments_Analyzer.ipynb
   ```

## Usage 📝
1. Execute all cells in the notebook to:
   - Scrape quotes from the web.
   - Analyze sentiment and generate visualizations.
   - Use the interactive search feature (run the `interactive_search()` cell).

2. Outputs:
   - Quotes data saved to `data/quotes.csv` (automatically created).
   - Visualizations displayed inline in the notebook.

## File Structure 📂
```
quotes-sentiment-analyzer/
├── Quotes_Sentiments_Analyzer.ipynb  # Main notebook
├── requirements.txt                 # Dependencies
├── data/                            # Output folder (auto-created)
│   └── quotes.csv                   # Scraped quotes
└── README.md
```

## Dependencies 📦
Listed in `requirements.txt`:
```
textblob==0.15.3
requests==2.26.0
beautifulsoup4==4.10.0
pandas==1.3.4
matplotlib==3.4.3
seaborn==0.11.2
tqdm==4.62.3
```

## Customization ⚙️
- Change the output path in `save_quotes()` (default: `data/quotes.csv`).
- Modify visualization styles in `visualize_data()` (e.g., colors, figure size).

## License 📜
MIT License. 

---

**Author**: [Mohamed-Taqy Salmi](https://linkedin.com/in/mohamedtaqysalmi)  
**Contribute**: PRs and issues welcome!  
```
