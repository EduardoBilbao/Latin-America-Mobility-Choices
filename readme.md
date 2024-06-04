# CS_Guadalajara Mobility Choices
A collaborative project between MIT City Science and University of Guadalajara (UdeG) 

## Table of Contents
1. [Overview](#overview)
2. [Installation](#installation)
3. [Running the Application](#running-the-application)

## Overview
This project consists of a Flask API that runs in a local Jupyter notebook environment, and a React App that interacts with this API. The Flask API is designed to run locally on port 3000.

## Installation

### Prerequisites
Make sure you have installed all of the following prerequisites on your development machine:

* Node Version Manager (NVM) - [Download & Install NVM](https://github.com/nvm-sh/nvm). Use the version v16.19.0 due to compatibility issues with later versions.
* Create a conda environment using the requirements.txt file

#### Running the Flask API

Open and run all cells in the app.ipynb notebook.

#### Installing the React App

1. Navigate to the /front_end/ directory.

2. Set the Node version to v16.19.0 using nvm. Run the following command in your terminal:

    ```bash
    nvm use 16.19.0
    ```

3. Install the project dependencies. Run the following command in your terminal:

    ```bash
    npm install
    ```

## Running the Application

#### Running the Flask API

1. Ensure the Jupyter notebook with the Flask API is running.

2. The API will be available at `http://localhost:3000`.

#### Running the React App

1. From the React app directory, start the app by running:

    ```bash
    npm start
    ```

2. The app will be available at `http://localhost:3001` (or the next available port).

Please ensure that the Flask API is running and accessible as the React app depends on it.
