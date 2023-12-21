<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield1]][linkedin-url1]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages">
    <img src="logo.png" alt="Logo" width="200" height="200">
  </a>

<h3 align="center">Skills: Programming with Advanced Computer Languages</h3>

  <p align="center">
    Stock Analysis and Portfolio Comparison Tool
    <br />
    <a href="https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages">View Demo</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Overview

[![Product Name Screen Shot][product-screenshot]](https://example.com)

This Python tool provides functionalities for analyzing stock performance, creating and comparing investment portfolios, and performing descriptive statistics analysis on major technology companies and the NASDAQ index.

Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `LH5399`, `Skills-Programming-with-Advanced-Computer-Languages`, `twitter_handle`, `linkedin_username`, `email_client`, `email`, `project_title`, `project_description`

<p align="right">(<a href="#readme-top">back to top</a>)</p>







<!-- GETTING STARTED -->
## Usage
The program consists of four main functions:

1. Import CSV
Allows users to import stock data from a CSV file.

2. Plot Stock Performance
Enables users to compare the stock performance of selected technology companies.

3. Create and Compare Portfolio
Users can create a virtual portfolio and compare its performance against the NASDAQ index.

4. Descriptive Statistics Analysis
Perform statistical analysis on selected stocks, including calculating volatility, correlation with NASDAQ, and annualized returns.

## Starting the Programm
Run the program with the following command:

```sh
python stock_analysis.py
```
Follow the prompts in the interactive interface to import data and choose the desired analysis function.

## How it works

### Setup
* Data Import (import_csv): Prompts the user to input the path to the CSV data file, loads the data, and sets up the mapping of company names to ticker symbols.
Functions
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


Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/LH5399/Skills-Programming-with-Advanced-Computer-Languages.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

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

