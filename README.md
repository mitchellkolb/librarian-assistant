
<h1 align="center">Librarian Assistant</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/mitchellkolb/librarian-assistant?color=B63E3A">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/mitchellkolb/librarian-assistant?color=B63E3A">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/mitchellkolb/librarian-assistant?color=B63E3A">

  <img alt="Github stars" src="https://img.shields.io/github/stars/mitchellkolb/librarian-assistant?color=B63E3A" />
</p>

<p align="center">
<img
    src="https://img.shields.io/badge/Typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"
    alt="Website Badge" />
<img
    src="https://img.shields.io/badge/Javascript-B7A622?style=for-the-badge&logo=javascript&logoColor=white"
    alt="Website Badge" />
<img
    src="https://img.shields.io/badge/Angular-B63E3A?style=for-the-badge&logo=angular&logoColor=white"
    alt="Website Badge" />
<img
    src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white"
    alt="Website Badge" />
<img
    src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"
    alt="Website Badge" />
<img
    src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=Windows 10&logoColor=white"
    alt="Website Badge" />
</p>

In this project, we develop a library assistance webapp that manages user registrations, book searches, holds, checkouts, book returns, etc, as well as storing all that information on a database. 

![project image](resources/jpenj.gif)

<details>
<summary style="color:#5087dd">Watch the Full Video Demo Here</summary>

[![Full Video Demo Here](https://img.youtube.com/vi/q_6WR5n7nQA/0.jpg)](https://www.youtube.com/watch?v=q_6WR5n7nQA)

</details>

---

# Table of Contents
- [What I Learned](#what-i-learned-in-this-project)
- [Tools Used / Development Environment](#tools-used--development-environment)
- [Team / Contributors / Teachers](#team--contributors--teachers)
- [How to Set Up](#how-to-set-up)
- [Project Overview](#project-overview)
- [Project Details](#project-details)
  - [Technical Plan](#technical-plan)
  - [Milestones](#milestones)
- [Results](#results)
- [Future Work](#future-work)
- [Acknowledgments](#acknowledgments)

---

# What I Learned in this Project
- How to develop a website using the Angular framework.
- Using PostgreSQL to store and retrieve data for the frontend.
- Programming using typescript, javascript, and html/css.
- Developing software using the SCRUM methodology.



# Tools Used / Development Environment
- Angular version 13.3.2
- Node.js version 16.14.2
- PostgreSQL version 12.9 (Ubuntu) or 14.2 (Windows)
- VS Code
- Terminal
- Windows 10





# Team / Contributors / Teachers
- [Mitchell Kolb](https://github.com/mitchellkolb)
- [Jose Robles](https://github.com/jose-robles2)
- [Nick Zheng](https://github.com/NicholasZ42)
- [Paul Swan](https://github.com/realPaulSwan)
- [Evan Smtih](https://github.com/EvanSmith2002)
- [Josh Konop](https://github.com/Joshua-Konop)
- Professor. Haipeng Cai





# How to Set Up
This project was implemented on our local machines:
- Clone this repository 
- Open terminal at the codebase `~.../librarian-assistant/JPENJ-322-Library-Project/`
- Install PostgreSQL and create a new local instance and use our sql files to setup the table schema.
- In `NodeJS/index.js` connect your database to the website in this file
- Ensure you have Node.js version 16.14.2 installed. You can download it from the [Node.js website](https://nodejs.org/). Check your version number with: `node -v` and `npm -v`
- Go into the NodeJS folder and use `npm install`
- Run the Express server with `node index.js`
- To setup the angular frontend go into the Angular folder and use `npm install`
- Run the application with `ng serve`





# Project Overview
This project utilizes Angular, Node.js, and PostgreSQL to create a comprehensive library management system. Our web application handles user registrations, book searches, holds, checkouts, returns, and more, with all data stored in a PostgreSQL database. This project was a collaborative effort by a team of six, aiming to streamline library operations.

# Project Details
The Librarian Assistant project is a web application designed to facilitate common library management tasks. It allows librarians to register users, search for books, place holds, check out and return books, and manage user and book data efficiently.

## Technical Plan
Our team used a multi-tier architecture, with Angular handling the client-side operations, Node.js serving as the server-side framework, and PostgreSQL managing the database. Our approach includes the following technologies and frameworks:
- **Angular**: For building the front-end interface.
- **Node.js**: As the server-side platform.
- **PostgreSQL**: For database management.
- **Express**: For handling server-side routing.
- **Cors**: For enabling cross-origin requests.
- **HTTPClient**: For managing HTTP requests within Angular.

### Milestones
In this project, we followed a structured development process divided into several milestones:
1. **Milestone 1**: Identified key tools, technologies, and the process model for the project.
2. **Milestone 2**: Defined requirements and created use case diagrams to model user interactions.
3. **Milestone 3**: Developed class diagrams and CRC index cards to define the system’s data structure.
4. **Milestone 4**: Designed the high-level architecture and key components.
5. **Milestone 5**: Elaborated on the design, including component and user interface design.
6. **Milestone 6**: Constructed the application and created usage instructions.
7. **Milestone 7**: Developed and executed test cases to ensure functionality and reliability.
8. **Milestone 8**: Presented the final product, including a demo and retrospective summary.

## Results
During development, our team successfully implemented a fully functional web application that met all project requirements. We were able to integrate various components effectively, allowing users to register, handling for book management and data processes. We also had some testing which allowed us to validated the system, confirming that our application performs as expected under different situations.

## Future Work
Future improvements could include:
- Enhancing the user interface to be more usable.
- Implementing advanced search functionalities, such as filtering by genre or publication date.
- Expanding the system to support multiple libraries within a single platform.
- Actually publishing the site as well.



--- 
# Acknowledgments
This codebase and all supporting materials was made as apart of a course for my undergrad at WSU for CPTS 322 - Software Design and Architecture in the Spring of 2021. This project was originally submitted to a campus controlled repository as all WSU assignments are. This repository serves as a backup place to showcase this project. The original repo is [linked here.](https://github.com/Joshua-Konop/JPENJ-322-Library-Project)


