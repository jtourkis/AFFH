# AFFH
Spacial Object Conversion, Mapping, and Basic Clustering/Autocorrelation Tests
 [![MIT License][license-shield]][license-url]
  [![LinkedIn][linkedin-shield]][linkedin-url]

<br />

  
  <h3 align="center">GIS/Spacial Data Analysis Using HUD AFFH Data</h3>
  
<p align="center">
  <a href="https://github.com/jtourkis/AFFH">
    <img src="Affordable.png" alt="AFFH" width="600" height="600" style="border:5px solid black">
  </a>
  <p align="center">
   
  
  <b>Goal:</b> This project uses AFFH census data with GIS/spacial data with a variety of analysis methods.
    <br />
    <a href="https://github.com/jtourkis/AFFH"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/jtourkis/AFFH">View Demo</a>
    ·
    <a href="https://github.com/jtourkis/AFFH/issues">Report Bug</a>
    ·
    <a href="https://github.com/jtourkis/AFFH/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

The project covers Spacial Object Conversion, Mapping, and Basic Clustering/Autocorrelation Tests.

### Built With

* [R](https://www.r-project.org) / [R Studio](https://www.rstudio.com)
* [sf](https://r-spatial.github.io/sf/)
* [sp](https://cran.r-project.org/web/packages/sp/index.html)
* [tmap](https://github.com/mtennekes/tmap)
* [spdep](https://cran.r-project.org/web/packages/spdep/index.html)
* [tigris](https://cran.r-project.org/web/packages/tigris/tigris.pdf)
* Many other packages.


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

List of required packages.

* pandas

* plotly

* seaborn

* matplotlib.pyplot


### Installation
 
1. Clone the repo

```sh
git clone https://github.com/jtourkis/AFFH.git
```
2. Install packages
```sh
pip install package
```


<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap
Using Affirmatively Furthering Fair Housing census tract data from HUD, this code performs the following tasks:

1) Use geo_id and TIGRIS to add spacial geometry and convert data to the proper SF/ SP data object for task;

2) Use TMap to visualize affordable rental units by census tract in Massachusetts;

3) Perform basic cluster analysis using local Morans I/local G-Stat and create interactive map emphasizing statistically significant regions. 


See the [open issues](https://github.com/github_username/repo/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

Note: The intial README Template was distributed under the MIT License. Copyright (c) 2018 Othneil Drew. [LICENSE](https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt)  for more information. 



<!-- CONTACT -->
## Contact

James Tourkistas - jmtourkistas@suffolk.edu

Project Link: [https://github.com/jtourkis/AFFH](https://github.com/jtourkis/AFFH)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Best-README-Template](https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md) 
* [HUD Affirmatively Furthering Fair Housing](https://www.hud.gov/program_offices/fair_housing_equal_opp/affh)
* [Urban Institute AFFH Data Repository](https://datacatalog.urban.org/dataset/data-and-tools-fair-housing-planning/resource/a74665c3-6fa0-4d84-9c1e-d40fc3cf0f8c)
* [An Introduction to R for Spatial Analysis and Mapping](https://uk.sagepub.com/en-gb/eur/an-introduction-to-r-for-spatial-analysis-and-mapping/book258267)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/jtourkis/MBTA-Ridership-Model/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/james-tourkistas-7127ba167/
[product-screenshot]: images/screenshot.png
