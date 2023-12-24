# Flipkart Mobiles Under 50000 Web Scraping

## Overview

This repository contains a Python script for web scraping mobile phone data from Flipkart. The script uses BeautifulSoup for web scraping and Pandas for data manipulation. The target is to gather information on mobile phones priced under 50000 from Flipkart, including product names, prices, descriptions, and reviews.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- Python
- BeautifulSoup
- Pandas
- Requests

You can install them using the following command:

```bash
pip install beautifulsoup4 pandas requests
```

### Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/flipkart-mobiles-web-scraping.git
```

2. Navigate to the project directory:

```bash
cd flipkart-mobiles-web-scraping
```

3. Run the script:

```bash
python flipkart_scraper.py
```

This will initiate the web scraping process and generate a CSV file containing the scraped data.

## Data Structure

The script extracts the following information:

- Product Name
- Prices
- Description
- Reviews

The data is then stored in a Pandas DataFrame and exported to a CSV file (`flipkart_mobile_under_50000.csv`).

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to Flipkart for providing the data for educational and research purposes.

Happy Coding! 🚀

---

Feel free to customize the README file according to your preferences and add any additional sections you think might be relevant to your project.
