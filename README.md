<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

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
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/vinicoli/profiles-rest-api">
    <img src="https://github.com/vinicoli/profiles-rest-api/assets/56003318/70985b15-17bc-4cfd-86c8-664f8fbc0cc3" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">profiles-rest-api</h3>

  <p align="center">
    A Profile RESTful API. 
    <br />
    <a href="https://github.com/vinicoli/profiles-rest-api"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/vinicoli/profiles-rest-api">View Demo</a>
    ·
    <a href="https://github.com/vinicoli/profiles-rest-api/issues">Report Bug</a>
    ·
    <a href="https://github.com/vinicoli/profiles-rest-api/issues">Request Feature</a>
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
    <!-- <li><a href="#usage">Usage</a></li> -->
    <!-- <li><a href="#roadmap">Roadmap</a></li> -->
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![api-screenshot](https://github.com/vinicoli/profiles-rest-api/assets/56003318/899a0e6f-b21e-4a19-b5ba-804d756de25d)

Profiles REST API is a project developed with Django REST framework to handle user profiles. This includes authentication, CRUD operations for users, and a feed for short texts. This project was developed as a learning method during my studies on REST APIs and Django REST framework.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Vagrant][Vagrant-shield]][Vagrant-url]
* [![VirtualBox][VirtualBox-shield]][VirtualBox-url]
* [![Python][Python-shield]][Python-url]
* [![Django][Django-shield]][Django-url]
* [![DRF][DRF-shield]][DRF-url]
* [![SQLite][SQLite-shield]][SQLite-url]
* [![VsCode][VsCode-shield]][VsCode-url]
* [![Git][Git-shield]][Git-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

To proceed with the installation, it is necessary to have the following pre-installed software on your machine:
* [Vagrant][Vagrant-url]
* [Oracle VirtualBox][VirtualBox-url]
* [Python][Python-url]
* [Git][Git-url]

### Installation

1. In a Git bash or terminal go to your workspace by typing:
   ```bash
   cd ~/workspace
   ```
2. Clone the repo:
   ```bash
   git clone https://github.com/vinicoli/profiles-rest-api.git
   ```
3. Go to the project workspace:
   ```bash
   cd ~/workspace/profile-rest-api
   ```
4. Start vagrant environment :
   ```bash
   vagrant up
   ```
5. Connect to machine via SSH:
   ```bash
   vagrant ssh
   ```
6. Create and activate virtual environement:
   ```bash
   python -m venv ~/venv && source ~/venv/bin/activate
   ```
7. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
8. Go to the project's root folder:
   ```bash
   cd /vagrant
   ```
9. Run the development server:
   ```bash
   python manage.py runserver 0.0.0.0:8000
   ```
10. Open the browser in the following link:
    ```bash
    http://127.0.0.1:8000/api
    ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
<!-- ## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->



<!-- ROADMAP -->
<!-- ## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/vinicoli/profiles-rest-api/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->



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



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Vinícius Oliveira - [@vini.coli](https://www.instagram.com/vini.coli/) - vinioliveira.web@gmail.com

LinkedIn: [Vinícius Oliveira][linkedin-url]

Project Link: [https://github.com/vinicoli/profiles-rest-api](https://github.com/vinicoli/profiles-rest-api)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Conventional Commits](https://www.conventionalcommits.org/)
* [Vagrant Cheat Sheet](https://acloudguru.com/blog/engineering/vagrant-cheat-sheet-get-started-with-vagrant)
* [Django Cheat Sheet](https://cheatography.com/ogr/cheat-sheets/django/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/vinicoli/profiles-rest-api.svg?style=for-the-badge
[contributors-url]: https://github.com/vinicoli/profiles-rest-api/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/vinicoli/profiles-rest-api.svg?style=for-the-badge
[forks-url]: https://github.com/vinicoli/profiles-rest-api/network/members
[stars-shield]: https://img.shields.io/github/stars/vinicoli/profiles-rest-api.svg?style=for-the-badge
[stars-url]: https://github.com/vinicoli/profiles-rest-api/stargazers
[issues-shield]: https://img.shields.io/github/issues/vinicoli/profiles-rest-api.svg?style=for-the-badge
[issues-url]: https://github.com/vinicoli/profiles-rest-api/issues
[license-shield]: https://img.shields.io/github/license/vinicoli/profiles-rest-api.svg?style=for-the-badge
[license-url]: https://github.com/vinicoli/profiles-rest-api/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/vinicoli
[product-screenshot]: images/screenshot.png
[Vagrant-shield]: https://img.shields.io/badge/Vagrant-1563FF?style=for-the-badge&logo=vagrant&logoColor=white
[Vagrant-url]: https://www.vagrantup.com/
[VirtualBox-shield]: https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white
[VirtualBox-url]: https://www.virtualbox.org/
[Python-shield]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=yellow
[Python-url]: https://www.python.org/
[Django-shield]: https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green
[Django-url]: https://www.djangoproject.com/
[DRF-shield]: https://img.shields.io/badge/Django_Rest_Framework-092E20?style=for-the-badge&logo=django&logoColor=green
[DRF-url]: https://www.django-rest-framework.org/
[SQLite-shield]: https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white
[SQLite-url]: https://www.sqlite.org/index.html
[VsCode-shield]: https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white
[VsCode-url]: https://code.visualstudio.com/
[Git-shield]: https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white
[Git-url]: https://git-scm.com/ 
