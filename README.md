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

<!-- PROJECT LOGO -->
<h3 align="center">👔 Jobly Backend 👔</h3>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#running-tests">Running Tests</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This is a RESTful API built using node/express to interact with a Postgres database. This API was built as the backend to be used by the [Jobly](https://github.com/nickorsi/react-ts-jobly-fronted-vite) frontend repo. Some of the features this API includes:
* Registers and authenticates users safely with the use of bcrypt hashing
* Uses JWT validation to authenticate and authorize users
* Throughly tested code with 99% coverage


The code is provided courtesy of [Rithm School](https://www.rithmschool.com/) as part of the curriculum material.

The API has the following endpoints:
* Authentication Routes:
  * ```POST/auth/register```: Registers a user providing valid data.
  * ```POST/auth/token```: Authenticates user via a validated JWT.
* Companies Routes:
  * ```POST/companies```: Adds a company with valid data.
  * ```GET/companies```: Retrieves all companies, can provide a search filter.
  * ```GET/companies/[handle]```: Retrieves a specified company.
  * ```PATCH/companies/[handle]```: Updates a specified company.
  * ```DELETE/companies/[handle]```: Deletes a specified company.
* Job Routes:
  * ```POST/jobs```: Adds a job with valid data.
  * ```GET/jobs```: Retrieves all jobs, can provide a search filter.
  * ```GET/jobs/[handle]```: Retrieves a specified job.
  * ```PATCH/jobs/[handle]```: Updates a specified job.
  * ```DELETE/jobs/[handle]```: Deletes a specified job.
* User Routes:
  * ```POST/jobs```: Adds a job with valid data.
  * ```GET/jobs```: Retrieves all jobs, can provide a search filter.
  * ```GET/jobs/[handle]```: Retrieves a specified job.
  * ```PATCH/jobs/[handle]```: Updates a specified job.
  * ```DELETE/jobs/[handle]```: Deletes a specified job.




<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
To get a local copy up and running follow these steps. Note this code is configured for a postgres database.

1. Using the terminal, clone this repo at your desired directory.

  ```sh
  $ git clone https://github.com/nickorsi/jobly-backend.git
  ```
2. Within this new directory, install the dependencies.

  ```sh
  $ npm install
  ```
3. Create the jobly database and seed it with randomized data using the provided sql file.

  ```sh
  $ psql -f jobly.sql
  ```
4. Run the server locally.

  ```sh
  $ npm run start
  ```

### Running Tests
To run the provided automated tests, navigate to the project directory and run this script in the terminal.

  ```sh
  $ npm run test
  ```

To see the test coverage provided by the automated tests, run this script in the terminal.

  ```sh
  $ npm run cov
  ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Nick Orsi
* [<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Linkedin Logo">](https://www.linkedin.com/in/nicholas-orsi-18ab8382/)
* [www.nickorsi.com](https://www.nickorsi.com/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
This code was provided by [Rithm School](https://www.rithmschool.com/) curriculum.

* [Best README Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
