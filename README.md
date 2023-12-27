# Google Sheet Clone

A simple web-based spreadsheet application inspired by Google Sheets.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Project Structure](#project-structure)
- [Usage](#usage)

## Description

This project is a clone of Google Sheets, providing a basic yet functional grid-based spreadsheet application. It allows users to create, edit, and manage multiple sheets with cell formatting, formulas, and cyclic dependency detection.

## Features

- **Grid Setup (`grid.js`):**
  - Create a customizable grid with rows and columns.
  - Clicking on cells updates the address bar.

- **Open and Save Functionality (`openSave.js`):**
  - Download the sheet data as a JSON file.
  - Upload a JSON file to load sheet data.

- **Sheet Handling (`sheetsHandling.js`):**
  - Add, remove, and switch between sheets.
  - Initialize sheet properties, cell data, and dependency matrix.

## Project Structure

- **`grid.js`:** Contains code for setting up the grid and handling cell interactions.

- **`openSave.js`:** Manages functionality for downloading and opening sheet data.

- **`sheetsHandling.js`:** Handles the creation, removal, and switching of sheets. Initializes sheet properties and data structures.

- **`cycleValidation.js`:** Provides functions for detecting cyclic dependencies in the sheet.

- **`cyclicPathTrace.js`:** Implements functions for tracing and highlighting cyclic paths.

- **`formula.js`:** Manages cell formula evaluation, updating UI, and handling formula-related actions.

## Usage
Open the project in a web browser
Open the index.html file in your preferred browser.

Interact with the spreadsheet:

    Add, edit, and delete cells.
    Use the address bar to navigate between cells.
    Download and upload sheet data.
