# Daily News Project

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The Daily News Project is a web application designed to provide users with the latest news articles from various sources. It aggregates news content and presents it in a user-friendly interface for easy browsing and reading.

## Features

- Fetches the latest news articles from multiple sources
- Categories for different types of news (e.g., technology, sports, entertainment)
- Search functionality to find specific news articles
- User-friendly and responsive design for both desktop and mobile devices

## Technologies Used

- Frontend: HTML, CSS, JavaScript, React
- Backend: Java
- API: News API
- Database: MongoDB (for user-specific features, if any)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/sanjaikrp/Daily-News.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Daily-News
    ```
3. Install the frontend dependencies:
    ```sh
    cd client
    npm install
    cd ..
    ```
4. Install the backend dependencies:
    ```sh
    npm install
    ```
5. Set up the environment variables:
    ```sh
    cp .env.example .env
    ```
    Fill in the required values in the `.env` file, including your News API key.
6. Start the development servers:
    ```sh
    npm run dev
    ```

## Usage

1. Open your web browser and navigate to `http://localhost:3000` for the frontend.
2. Browse through the latest news articles from various categories.
3. Use the search functionality to find specific news articles of interest.
