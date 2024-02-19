# Google Search Scraper

This Python script performs Google searches for specific queries and scrapes the search results. It utilizes the Google Custom Search JSON API to retrieve search results.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Kutta22/Google-Search-Scraper.git
    ```

2. Navigate to the project directory:

    ```bash
    cd google-search-scraper
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Obtain Google API Key and Custom Search Engine ID:
   
   You need to obtain a Google API Key and a Custom Search Engine ID to use this script. Follow the instructions [here](https://developers.google.com/custom-search/v1/overview) to create a Custom Search Engine and obtain the API Key.

2. Update the API Key and Custom Search Engine ID in the script:

    ```python
    # Google API Key and Custom Search Engine ID
    api_key = "Your Google API Key"
    cx = "Your Custom Search Engine ID"
    ```

3. Define your search queries:

    ```python
    # List of queries
    queries = [
        "Canoo company background and history",
        "Canoo executive team and leadership",
        ...
    ]
    ```

4. Run the script:

    ```bash
    python main.py
    ```

5. The script will perform Google searches for each query, scrape the search results, and save the combined data to a CSV file named `canoo_data.csv`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
