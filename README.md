# finance-sentiment-ai

This repository contains the code and analysis for the Week 1 Challenge of the 10 Academy AI Mastery program. It focuses on analyzing financial news sentiment and its correlation with stock price movements. By leveraging NLP techniques and financial data analysis, it aims to enhance predictive analytics capabilities for financial forecasting.

# finance-sentiment-ai

This repository contains the code and analysis for the Week 1 Challenge of the 10 Academy AI Mastery program. It focuses on analyzing financial news sentiment and its correlation with stock price movements. By leveraging NLP techniques and financial data analysis, it aims to enhance predictive analytics capabilities for financial forecasting.

## Project Structure

The project is organized as follows:

- `data/`: Contains the raw and processed data files.
- `notebooks/`: Jupyter notebooks for data analysis and visualization.
  - `news analysis/`: Contains notebooks for analyzing financial news.
    - `time_series_analysis.ipynb`: Time series analysis of news articles.
    - `text_analysis.ipynb`: Sentiment analysis and topic modeling of news headlines.
    - `publisher_analysis.ipynb`: Analysis of the most active publishers and their sentiment.
    - `descriptive_statistics.ipynb`: Basic descriptive statistics of the dataset.
- `src/`: Source code for data processing and analysis.
- `README.md`: Project overview and setup instructions.

## Setup Instructions

### Prerequisites

Ensure you have the following installed:

- Python 3.7 or higher
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/finance-sentiment-ai.git
   cd finance-sentiment-ai
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```
But install TA-Lib separately it is removed from reuqieremnts.txt, because it requires further step.

### Running the Project

1. **Start Jupyter Notebook:**

   ```bash
   jupyter server
   ```

2. **Open the notebooks in VS code editor:**

   Navigate to the `notebooks/news analysis/` directory and open the following notebooks in order:

   - `time_series_analysis.ipynb`
   - `text_analysis.ipynb`
   - `publisher_analysis.ipynb`
   - `descriptive_statistics.ipynb`

   choose the kernel the exisitng jupyter server and enter its url and password (token) of jupyter server on vs code.

3. **Run the cells:**

   Execute the cells in each notebook to perform the analysis. The notebooks are organized to guide you through the data loading, processing, analysis, and visualization steps.
