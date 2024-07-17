
# API Testing


## Table of content
- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation and Setup](#installation-and-setup)
    - [Postman](#postman)
    - [Node.js](#node.js)
    - [Newman](#newman)
- [Project Installation Steps](#project-installation-steps)
- [API Documentation](#api-documentation)
- [Description of API calls and tests](#description-of-api-calls-and-tests)
- [Report Generation](#report-generation)
    - [Process of Report Generation](#process-of-report-generation)
    - [Report of the project](#report-of-the-project)
- [Contact](#contact)

## Overview
This repository demonstrates API testing using Postman and Newman. The tests cover a range of HTTP methods, including POST, GET, DELETE, and PUT, ensuring a thorough assessment of the API's capabilities.



## Prerequisites
- [Postman](https://www.postman.com/downloads/)
- [Node.js](https://nodejs.org/en/download/package-manager)
- Newman


## Installation and Setup
### Postman
- Download [Postman](https://www.postman.com/downloads/) from the official website
- Run the installer and complete set up.
- Launch Postman and sign in
### Node.js
- Download [Node.js](https://nodejs.org/en/download/package-manager) from the official website.
- Run the installer and complete set up.
- Verify Node.js installation by running node --version in a terminal.
### Newman
- Prerequisites: Node.js
- Install Newman globally by running the following npm command in terminal
```
npm install -g newman

```
- Verify Newman installation by running newman --version in a terminal.

## Project Installation Steps
Follow these steps to set up and start using the framework

- [Fork](https://github.com/tanjinarahmanprova/api-testing.git) the repository.
- Clone
```
git clone https://github.com/tanjinarahmanprova/api-testing.git
```
- Import the project into postman.
- Make any desired changes or additions to the project.

## API Documentation
- [Postman API Documentation](https://documenter.getpostman.com/view/32325704/2sA3e1BqSV)


## Description of API calls and tests

## Report Generation
### Process of report generation
- Install the newman reporter packages by running the following commands in terminal.
```
npm install -g newman-reporter-html
npm install -g newman-reporter-htmlextra

```
- Export collection and environment from Postman in a folder.
- Open a terminal in that folder and run the following commands to generate reports.

```
newman run CollectionName.json -e EnvironmentName.json -r cli,html
newman run CollectionName.json -e EnvironmentName.json -r cli,htmlextra

```

### Report of the project
- To generate report for this project run the following command in terminal.
```
newman run Tanjina_01634816794.postman_collection.json -e Tanjina_01634816794.postman_environment.json -r cli,htmlextra
```
![r1](https://github.com/user-attachments/assets/21fb8ffb-0262-4e7b-8f9d-af95e435169c)
![r2](https://github.com/user-attachments/assets/65c9efe8-7f2c-4c9c-abce-8a6451415624)
![r3](https://github.com/user-attachments/assets/4065e9be-248f-4395-9be2-344c37e87cf9)



## Contact
For questions or feedback, please feel free to reach out:
- **GitHub**: [Tanjina Rahman](https://github.com/tanjinarahmanprova)
- **Email**: [rahmantanjina983@gmail.com](mailto:rahmantanjina983@gmail.com)
- **LinkedIn**: [Tanjina Rahman](https://www.linkedin.com/in/tanjina-rahman-a53662191/)


