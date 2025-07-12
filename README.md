<!-- Improved compatibility of back to top link -->
<a id="readme-top"></a>
<div align="center">

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
</div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">📘 Web Scraping Using Python</h3>

  <p align="center">
    A Python script to extract book details from Flipkart and store them in Excel.
    <br />
    <a href="https://github.com/MalisettyBhavani/Web-Scraping-Using-Python"><strong>Explore the repo »</strong></a>
    <br />
    <br />
    <a href="#usage">View Usage</a>
    ·
    <a href="https://github.com/MalisettyBhavani/Web-Scraping-Using-Python/issues">Report Bug</a>
    ·
    <a href="https://github.com/MalisettyBhavani/Web-Scraping-Using-Python/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This project is a web scraping utility built with Python to extract structured product data—specifically, **book listings**—from the e-commerce platform **Flipkart**. Leveraging the **BeautifulSoup** library for HTML parsing and **urllib** for making HTTP requests, the script automates the process of collecting publicly available data such as:

- **Book titles**
- **Current selling prices**
- **Original (discounted) prices**
- **User ratings**
- **Review counts**

The extracted information is programmatically written into a structured **Excel spreadsheet** using the `openpyxl` library. This enables easy data storage, visualization, and downstream processing or analysis.

### ✨ Key Use Cases:
- Perform **competitive analysis** on book pricing
- Track discounts or price changes over time
- Build datasets for **natural language processing** or **recommender systems**
- Extract features for **data mining** or **machine learning** tasks
- Conduct sentiment or trend analysis based on review metadata

### 💡 Technical Highlights:
- Uses `urllib.request` with SSL context handling to manage HTTPS requests safely
- Parses and navigates the DOM tree using CSS selectors with BeautifulSoup
- Employs `openpyxl` for Excel I/O operations, allowing precise cell-level control
- Modular design for scraping different HTML elements, making it easy to scale or adapt to other product categories

This project serves as a foundational tool for anyone working on **data engineering**, **data scraping**, or **ETL (Extract, Transform, Load)** pipelines in the context of real-world web data.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With

* [![Python][Python-badge]][Python-url]
* [![BeautifulSoup][BS-badge]][BS-url]
* [![OpenPyXL][OpenPyXL-badge]][OpenPyXL-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

Install required packages:
```sh
pip install beautifulsoup4 openpyxl
```

### Installation

1. Clone the repo
```sh
git clone https://github.com/MalisettyBhavani/Web-Scraping-Using-Python.git
```
2. Create an Excel file `Flipkart_Books.xlsx` at `F:\projects\`
3. Add a sheet named `Books` with headers in columns A to E
4. Run the script:
```sh
python project.py
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

This script is designed to scrape product listings from Flipkart and extract key attributes related to books. Upon execution, it performs the following tasks:

- Retrieves the **book title** using semantic CSS selectors
- Captures the **current selling price** and any **original discounted price** if available
- Gathers the **user rating score** and the **total number of reviews**
- Writes the extracted data in tabular format into a preformatted Excel workbook

The final output is saved in an Excel spreadsheet (`Flipkart_Books.xlsx`) under the `Books` sheet. This structured format enables easier integration with analytics tools and data pipelines.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Scrape book data from Flipkart
- [x] Save data to Excel
- [ ] Add GUI interface
- [ ] Add category filters
- [ ] Make file paths OS-independent

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are welcome!
1. Fork the repo
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

**Bhavani Malisetty**  
**Email: bmalisetty@unomaha.edu** 
[GitHub](https://github.com/MalisettyBhavani)  
[LinkedIn](https://linkedin.com/in/malisettybhavani)

Project Link: [Web Scraping Using Python](https://github.com/MalisettyBhavani/Web-Scraping-Using-Python)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/MalisettyBhavani/Web-Scraping-Using-Python.svg?style=for-the-badge
[contributors-url]: https://github.com/MalisettyBhavani/Web-Scraping-Using-Python/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/MalisettyBhavani/Web-Scraping-Using-Python.svg?style=for-the-badge
[forks-url]: https://github.com/MalisettyBhavani/Web-Scraping-Using-Python/network/members
[stars-shield]: https://img.shields.io/github/stars/MalisettyBhavani/Web-Scraping-Using-Python.svg?style=for-the-badge
[stars-url]: https://github.com/MalisettyBhavani/Web-Scraping-Using-Python/stargazers
[issues-shield]: https://img.shields.io/github/issues/MalisettyBhavani/Web-Scraping-Using-Python.svg?style=for-the-badge
[issues-url]: https://github.com/MalisettyBhavani/Web-Scraping-Using-Python/issues
[Python-badge]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[BS-badge]: https://img.shields.io/badge/BeautifulSoup-4B0082?style=for-the-badge
[BS-url]: https://pypi.org/project/beautifulsoup4/
[OpenPyXL-badge]: https://img.shields.io/badge/OpenPyXL-1D6F42?style=for-the-badge
[OpenPyXL-url]: https://openpyxl.readthedocs.io/
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/bhavani-malisetty/
