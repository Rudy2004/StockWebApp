# Stock Simulator Website

## Overview

This is a simple stock simulator website built using Flask. The application allows users to simulate buying and selling stocks with virtual money. Users can create accounts, view stock prices, make transactions, and track their portfolio.

## Features

- User registration and authentication
- Stock price retrieval from an external API
- Virtual money balance for users
- Buy and sell stocks functionality
- Portfolio tracking

## Technologies Used

- Flask: a micro web framework for Python
- PostgreSQL: a lightweight relational database
- Bootstrap: for front-end styling
- TweleveData API: for retrieving stock prices

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Rudy2004/StockWebApp.git

   Navigate to the project directory:
   cd StockWebApp

   Install dependencies:
   pip install -r requirements.txt

   Set up environment variables:

   Create a file named .env in the project root and add the following with your own Secret Key:
   FLASK_APP=app
   FLASK_ENV=development
   SECRET_KEY=your_secret_key

   Run the application:
   flask run
    

