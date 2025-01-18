# **LINA AI Lyrics Generator: System Requirements**

To run the LINA AI Lyrics Generator, the minimum system requirements should cover basic Python execution, web scraping, and OpenAI API interactions. Below are the recommended specifications:

## **Hardware Requirements**:
- **Processor (CPU)**:
  - Minimum: Intel Core i5 or AMD Ryzen 5
  - Recommended: Intel Core i7 or AMD Ryzen 7 for better performance when processing large datasets.
- **Memory (RAM)**:
  - Minimum: 8 GB
  - Recommended: 16 GB (especially if processing many lyrics at once).
- **Storage**:
  - Minimum: 500 MB free disk space for Python libraries and project files.
  - Recommended: 1 GB or more for handling large datasets or additional resources like logs and cached data.
- **Internet Connection**:
  - Required for fetching lyrics from Google and interacting with the OpenAI API.

## **Software Requirements**:
- **Operating System**:
  - Windows 10 or later
  - macOS 10.14 (Mojave) or later
  - Linux (Ubuntu 20.04 or later recommended)
- **Python**:
  - Version: 3.7 or higher (Recommended: Python 3.9 or 3.10 for better compatibility with libraries).
- **Python Libraries**:
  - `requests`: For fetching web data (lyrics).
  - `beautifulsoup4`: For parsing HTML content.
  - `openai`: For interacting with OpenAI's GPT models.
  - `pandas`: For data analysis (if needed).
  - `nltk` or `spaCy` (optional for advanced text processing).

## **Python System Requirements**:
Ensure Python 3.7 or higher is installed. You can check your Python version using the command:
```bash
python --version
# or
python3 --version
