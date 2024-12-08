# Kanban Board

## Description
```md
This project is is to add authentication with JWT to an existing Kanban board application.
```

## User Story
```md
- AS A member of an agile team
- I WANT a Kanban board with a secure login
- SO THAT I can securely access and manage my work tasks 
```


## Table of Contents

- [Introduction](#introduction)
- [Technology](#technology)
- [Usage](#usage)
- [Contact](#credits)
- [License](#license)

## Introduction
GIVEN a Kanban board with a secure login page
WHEN I load the login page
THEN I am presented with form inputs for username and password
WHEN I enter my valid username and password
THEN I am authenticated using JSON Web Tokens (JWT) and redirected to the main Kanban board page
WHEN I enter an invalid username or password
THEN I am presented with an error message indicating that the credentials are incorrect
WHEN I successfully log in
THEN a JWT is stored securely in the client's local storage for subsequent authenticated requests
WHEN I log out
THEN the JWT is removed from the client's local storage and I am redirected to the login page
WHEN I try to access the Kanban board page without being authenticated
THEN I am redirected to the login page
WHEN I remain inactive for a defined period
THEN my session expires, the JWT is invalidated, and I am redirected to the login page upon my next action
Mock-Up
![alt text]()


## Technology
[![React](https://img.shields.io/badge/Framework-React-00ff00?style=plastic&logo=React&logoWidth=10)](https://reactjs.org/)
[![Render Status](https://img.shields.io/badge/Deployed%20on-Render-blue?style=plastic&logo=render&logoWidth=10)](https://render.com/)
[![TypeScript](https://img.shields.io/badge/Language-TypeScript-00ff00?style=plastic&logo=TypeScript&logoWidth=10)](https://www.typescriptlang.org/)
[![npm](https://img.shields.io/badge/Tools-npm-ff0000?style=plastic&logo=npm&logoWidth=10)](https://www.npmjs.com/)
[![VS Code](https://img.shields.io/badge/IDE-VSCode-ff0000?style=plastic&logo=VisualStudioCode&logoWidth=10)](https://code.visualstudio.com/docs)

## Usage
- [Github Repo](https://github.com/dcruzel/kanbanboard)
- [Website]()

## Resources

- Activity from bootcamp used 


## Contact

Elizabeth D'Cruz
- [Github Profile](https://github.com/dcruzel)
- [Email](Liz.c.dcruz@gmail.com)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

