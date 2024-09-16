<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="https://yt3.googleusercontent.com/R9tQgdmoPESZkadCeUbhI5OiSdPykuRjaP2PcfbLDDmwxqL5i1tpE_9vzNncELnN3A696_KRjrA=s900-c-k-c0x00ffffff-no-rj" alt="Swag Labs Logo" width="80" height="80">
  </a>

<h3 align="center">SWAG LABS Webshop</h3>

  <p align="center">
    This is the repo of the automated test!
    <br />
    <a href="https://www.saucedemo.com/"><strong>Explore the SUT »</strong></a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#made-with">Made With</a></li>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contributors">Contributors</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![SUT Screen Shot][sut-screenshot]](https://saucedemo.com)

This project consists of automated tests using **Page Factory** design pattern, **Selenium (Grid)** and **BDD** approach for a web application called Swag Labs (https://www.saucedemo.com/).
On this website you can log in with already existing users, order different products, and simulate ordering the products you have in your shopping cart.

[View Test Results](Test%20Results%20-%20RunAllTests.html)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Made With

This section lists any major frameworks/libraries used in this project. We also mention certain approaches or design patterns which are important for automated tests.

- **Frameworks & Libraries**
    * ![JUnit][junit]
    * ![Selenium][selenium]
    * ![SeleniumGrid][selenium-grid]
      * ![Docker][docker]
    * ![Cucumber][cucumber]
- **Design patterns & Approaches**
    * ![PageFactory][page-factory]
    * ![Bdd][bdd]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

Before installing the project, make sure you have Docker installed on your machine.
Docker can be downloaded and installed from the official Docker website. Here are the links to download Docker for different operating systems:

[Docker Desktop for Windows](https://docs.docker.com/desktop/install/windows-install/)

[Docker Desktop for Mac](https://docs.docker.com/desktop/install/mac-install/)

[Docker Desktop for Linux](https://docs.docker.com/desktop/install/linux-install/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Clone the repo
   ```sh
   git clone https://github.com/CodecoolGlobal/test-automation-webshop-in-beta-general-TiborKovari.git
   ```
2. Start docker-compose file to set up Selenium Grid
   ```sh
   docker compose up
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

You can run every written automated test by starting the `RunAllTests.java` file.

_It is located in the `src/test/java/com/codecool/webshop/` folder_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTORS -->
## Contributors

<a href="https://github.com/CodecoolGlobal/test-automation-webshop-in-beta-general-TiborKovari/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=CodecoolGlobal/test-automation-webshop-in-beta-general-TiborKovari" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[sut-screenshot]: src/test/resources/screenshots/product_list.png
[junit]: https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white
[selenium]: https://img.shields.io/badge/Selenium-43B02A.svg?style=for-the-badge&logo=selenium&logoColor=white
[selenium-grid]: https://img.shields.io/badge/Selenium_Grid-white?style=for-the-badge&logo=selenium&logoColor=purple
[docker]: https://img.shields.io/badge/-Docker-blue?logo=docker&style=for-the-badge
[cucumber]: https://img.shields.io/badge/Cucumber-43B02A?style=for-the-badge&logo=cucumber&logoColor=white
[page-factory]: https://img.shields.io/badge/Page_Factory-000000?style=for-the-badge&logo=&logoColor=white
[bdd]: https://img.shields.io/badge/Behaviour_Driven_Development_(BDD)-000000?style=for-the-badge&logo=&logoColor=white
