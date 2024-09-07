# Information Retrieval System

## Overview
This repository contains an information retrieval system implemented through a Jupyter notebook. The system demonstrates web crawling, text preprocessing, document indexing, and various search techniques including cosine similarity and Boolean search. Additionally, it features a spelling correction mechanism for more robust query handling.

## Repository Structure
```bash
information-retrieval-system/
├── notebooks/
│   └── information_retrieval_system.ipynb
├── requirements.txt
└── README.md
```


## Notebook

### `information_retrieval_system.ipynb`

This notebook showcases the implementation of the information retrieval system. It includes the following components:

1. **Crawler**: Fetches and crawls web pages to collect data.
2. **Preprocessor**: Cleans and preprocesses text data from the crawled pages.
3. **Indexer**: Creates an inverted index and positional index for the documents.
4. **Searcher**: Implements search functionalities including cosine similarity and Boolean search.
5. **TolerantRetrieval**: Provides spelling correction for queries using edit distance.

### Features

- **Web Crawling**: Collects documents from specified URLs.
- **Text Preprocessing**: Cleans and tokenizes text, removes stopwords, and applies stemming.
- **Indexing**: Builds an inverted index and positional index for efficient searching.
- **Search Techniques**:
  - **Cosine Similarity**: Retrieves documents based on similarity to the query.
  - **Boolean Search**: Retrieves documents based on Boolean operators (AND, OR, NOT).
- **Spelling Correction**: Handles misspelled words in queries using edit distance.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required packages listed in `requirements.txt`

### Installation

1. Clone the Repository:

    ```bash
    git clone https://github.com/MinaIbrahim10/information-retrieval-system.git
    ```

2. Navigate to the Repository:

    ```bash
    cd information-retrieval-system
    ```

3. Install Dependencies:

    Install the required packages using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Open the notebook in Jupyter Notebook or JupyterLab:

    ```bash
    jupyter notebook
    ```

2. Run the cells in the `information_retrieval_system.ipynb` notebook to execute the information retrieval system.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contributing

Contributions are welcome! Please follow the standard GitHub workflow for contributions:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## Contact

For any questions or feedback, you can reach me at minaibrahim190@gmail.com.
