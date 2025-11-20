Overview

This project is a Password protected desktop-style file management application built using web technologies.
When you run it, it behaves like a standalone software:

A full UI for navigating folders
Password protected
File grid preview
Context menus
Folder tree rendering
Basic file operations handled in the frontend

The goal is simple: provide a lightweight, browser-based file explorer UI that feels like a native application.

Project Structure

Your project should look like this (simplified):
Project/
│── package.json
│── package-lock.json
│── main.js
│── renderer.js
│── root/
│   └── 
│── config
│── views/
│   ├── index.css
│   ├── index.html
│   ├── enterPassword.html
│   └── setPassword.html
└── README.md


Where Your Files Go
Files stores in root directory
password store in config file with encryped key

before running create a root folder
Installation:-
After cloning the project, install dependencies:
npm install
This recreates the node_modules folder you intentionally excluded from GitHub.
To start the project in development mode:
npm start
