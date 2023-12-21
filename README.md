<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages">
    <img src="logo.png" alt="Logo" width="200" height="200">
  </a>

<h3 align="center">Skills: Programming with Advanced Computer Languages</h3>

  <p align="center">
    Stock Analysis and Portfolio Comparison Tool with 3 functions for the Big Five Dataset
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#Overview">Overview</a>
    </li>
    <li>
      <a href="#Features">Features</a>
    </li>
    <li>
      <a href="#Installation">Installation</a>
    </li>
    <li>
      <a href="#Starting the Programm">Starting the Programm</a>
    </li>
    <li>
      <a href="#How it works">How it works</a>
    </li>
      <ul>
        <li><a href="#Setup">Setup</a></li>
      </ul>
      <ul>
          <li><a href="#Functions">Functions</a></li>
        </ul>
      <ul>
          <li><a href="#User Interface">User Interface</a></li>
        </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## Overview

This Python tool provides comprehensive functionalities for analyzing stock performance, creating, and comparing investment portfolios, and performing descriptive statistics analysis. It focuses on major technology companies and includes functionalities for comparing with the NASDAQ index.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Features
The program consists of four main functions:

1. Data Import
Allows users to import stock data from a CSV file.

2. Plot Stock Performance
Enables users to compare the stock performance of selected technology companies.

3. Create and Compare Portfolio
Users can create a virtual portfolio and compare its performance against the NASDAQ index.

4. Descriptive Statistics Analysis
Perform statistical analysis on selected stocks, including calculating volatility, correlation with NASDAQ, and annualized returns.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Installation
To run this program, ensure you have Python installed along with the following libraries:

* pandas
* matplotlib
* numpy
Use the following command to install these libraries:

```sh
pip install pandas matplotlib numpy
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Starting the Programm
Run the program with the following command:

```sh
python stock_analysis.py
```
Follow the prompts in the interactive interface to import data and choose the desired analysis function.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## How it works

### Setup
* Data Import (import_csv): Prompts the user to input the path to the CSV data file, loads the data, and sets up the mapping of company names to ticker symbols.

### Functions
1. Plot Stock Performance (plot_stock_performance):

* Users select companies and specify time frames for analysis.
* Offers options to plot data on a logarithmic or relative scale.
* Includes an option to benchmark against the NASDAQ index.

2. Create and Compare Portfolio (create_and_compare_portfolio):

* Users create a virtual investment portfolio by selecting companies and allocating percentages.
* Compares the portfolio's performance to the NASDAQ index over the specified period.

3. Descriptive Statistics Analysis (descriptive_statistics_analysis):

* Performs statistical analysis on user-selected stocks.
* Calculates key metrics like highest/lowest prices, volatility, and correlation with NASDAQ.
<!-- User Interface -->
### User Interface
* The main function serves as the entry point, offering a menu to choose among the different functionalities.
* Users can opt to compare stock performance, create a portfolio, analyze descriptive statistics, or exit the program.



<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [x] Python code
    - [x] Stock performance
    - [x] Portfolio
    - [x] Descriptive Statistics 
- [x] Readme



<p align="right">(<a href="#readme-top">back to top</a>)</p>






<!-- CONTACT -->
## Contact

Leopold Huberth - leopold.huberth@student.unisg.ch

Dominik De Marco - dominik.demarco@student.unisg.ch

Project Link: [https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages](https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages)

<p align="right">(<a href="#readme-top">back to top</a>)</p>









<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/LH5399/Skills-Programming-with-Advanced-Computer-Languages.svg?style=for-the-badge
[contributors-url]: https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/LH5399/Skills-Programming-with-Advanced-Computer-Languages.svg?style=for-the-badge
[forks-url]: https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages/network/members
[stars-shield]: https://img.shields.io/github/stars/LH5399/Skills-Programming-with-Advanced-Computer-Languages.svg?style=for-the-badge
[stars-url]: https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages/stargazers
[issues-shield]: https://img.shields.io/github/issues/LH5399/Skills-Programming-with-Advanced-Computer-Languages.svg?style=for-the-badge
[issues-url]: https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages/issues
[license-shield]: https://img.shields.io/github/license/LH5399/Skills-Programming-with-Advanced-Computer-Languages.svg?style=for-the-badge
[license-url]: https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages/blob/master/LICENSE.txt
[linkedin-shield1]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url1]: https://www.linkedin.com/in/l-huberth
[linkedin-shield2]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url2]: https://www.linkedin.com/in/dominik-de-marco/
[product-screenshot]: images/screenshot.png

