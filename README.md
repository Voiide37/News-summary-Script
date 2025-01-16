# News Summarizer

This is a simple news summarizer application built using Python and Tkinter. It fetches an article from a given URL, summarizes it, and performs sentiment analysis.

## Requirements

- Python 3.x
- Tkinter
- NLTK
- TextBlob
- Newspaper3k

## Installation

1. Clone the repository or download the script.
2. Install the required Python packages using pip:

    ```sh
    pip install nltk textblob newspaper3k
    ```

3. Download the necessary NLTK data:

    ```python
    import nltk
    nltk.download('punkt')
    ```

## Usage

1. Run the script:

    ```sh
    python main.py
    ```

2. Enter the URL of the news article you want to summarize in the URL field.
3. Click the "Summarize" button.
4. The application will display the title, authors, publish date, summary, and sentiment of the article.

## Example

![News Summarizer GUI](News_summarizer_News_GUI.png)

## License

This project is licensed under the MIT License.