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
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This project scrapes book listings from Flipkart using Python. It extracts book titles, prices, ratings, and review counts, storing them in an Excel file with the help of BeautifulSoup and OpenPyXL.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [Python](https://www.python.org/)
* [BeautifulSoup](https://pypi.org/project/beautifulsoup4/)
* [OpenPyXL](https://openpyxl.readthedocs.io/)

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

The script scrapes:
- Book name
- Current price
- Original price
- Ratings
- Number of reviews

The data is saved in an Excel spreadsheet under the "Books" sheet.

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

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

**Bhavani Malisetty**  
[GitHub](https://github.com/MalisettyBhavani)  
[LinkedIn](https://linkedin.com/in/malisettybhavani)

Project Link: [Web Scraping Using Python](https://github.com/MalisettyBhavani/Web-Scraping-Using-Python)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Choose an Open Source License](https://choosealicense.com)
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
[license-shield]: https://img.shields.io/github/license/MalisettyBhavani/Web-Scraping-Using-Python.svg?style=for-the-badge
[license-url]: https://github.com/MalisettyBhavani/Web-Scraping-Using-Python/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/bhavani-malisetty/
