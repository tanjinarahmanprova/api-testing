
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
    - [Get Student Info](#get-student-info)
    - [Create Student](#get-booking-info)
    - [Get Specific Student's Info](#get-specific-student's-info)
    - [Create Technical Skills](#create-technical-skills)
    - [Create Student Address](#create-student-address)
    - [Get Final Student Details](#get-final-student-details)
    
- [Report Generation](#report-generation)
    - [Process of Report Generation](#process-of-report-generation)
    - [Report of the project](#report-of-the-project)
- [Contact](#contact)

## Overview
This repository demonstrates API testing using Postman and Newman. The tests cover a range of HTTP methods ensuring a thorough assessment of the API's capabilities.



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
git https://github.com/tanjinarahmanprova/api-testing.git
```
- Import the project into postman.
- Make any desired changes or additions to the project.

## API Documentation
- [Postman API Documentation](https://documenter.getpostman.com/view/32325704/2sA3e1BqSV)

## Description of API calls and tests
### Get Student Info
GET method is used to fetch student info.  Some tests are performed for status code validation and length of the response.

![g1](https://github.com/user-attachments/assets/0ad433a2-2979-437c-b1ba-9de6645f8640)
![g2](https://github.com/user-attachments/assets/3db14dff-82d1-4386-bb0a-8cef799a198c)
### Create Student
POST method is used to create student. Dynamic data is generated using Pre-request script and these dynamic data is saved in environment variables. Some tests are performed for status code validation.

![cs1](https://github.com/user-attachments/assets/6dd4e885-3d3d-43f4-9f4e-a56fbc4e5851)
![cs2](https://github.com/user-attachments/assets/088a99c0-6deb-4daa-8894-d2aae493269d)

### Get Specific Student's Info
GET method is used to fetch a specific student's info.  Some tests are performed for status code, id, first name, middle name, last name, date of birth validation.

![gss1](https://github.com/user-attachments/assets/90967463-f382-4fb7-a432-3060946b6576)
![gss2](https://github.com/user-attachments/assets/e4e1906f-c251-45ae-888b-94f02c474fbd)

### Create Technical Skills
POST method is used to create technical skills. Dynamic data is generated using Pre-request script and these dynamic data is saved in environment variables. Some tests are performed for status code validation.

![cts1](https://github.com/user-attachments/assets/147b9fc4-f269-4bd4-abc3-078bd447fb61)
![cts2](https://github.com/user-attachments/assets/1dd0bf9d-4be8-411d-bde1-b9333ae4af50)
![cts3](https://github.com/user-attachments/assets/d072edd7-5b82-4218-a598-224fbdc10ccd)
### Create Student Address
POST method is used to create student address. Dynamic data is generated using Pre-request script and these dynamic data is saved in environment variables. Some tests are performed for status code, status and message field value validation.

![csa1](https://github.com/user-attachments/assets/91c29ff9-0742-49ec-b23b-e6bb4a28af5f)
![csa2](https://github.com/user-attachments/assets/54413d76-5971-4488-97c9-3f75d53cb19d)
![csa3](https://github.com/user-attachments/assets/3bb1a4c6-8fce-425d-bdb4-c89c46ba5c4d)

### Get Final Student Details
GET method is used to fetch a final student details.  Some tests are performed for status code, Language, Year of Experience, House Number, City, Country, Mobile, Current Address validation.

![gfs1](https://github.com/user-attachments/assets/456d07db-e30e-42d5-834d-b26e8c90c5be)
![gfs2](https://github.com/user-attachments/assets/725560ec-46e8-471f-bc62-1820f7803ef4)
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
![rp1](https://github.com/user-attachments/assets/5a52d1b4-ecbf-419a-adab-2f48241390fa)
![rp2](https://github.com/user-attachments/assets/6f28ce75-0136-435b-996e-6df9fd84251d)
![rp3](https://github.com/user-attachments/assets/13eccd3a-bbce-4f51-a235-55a15738eb9e)

## Contact
For questions or feedback, please feel free to reach out:
- **GitHub**: [Tanjina Rahman](https://github.com/tanjinarahmanprova)
- **Email**: [rahmantanjina983@gmail.com](mailto:rahmantanjina983@gmail.com)
- **LinkedIn**: [Tanjina Rahman](https://www.linkedin.com/in/tanjina-rahman-a53662191/)


