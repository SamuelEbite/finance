# finance
 
Finance is a web application that allows users to manage their personal finances. Users can register for an account, add funds to their balance, buy and sell stocks, and view their transaction history. The application also integrates with the IEX Cloud API to provide real-time stock prices.

Prerequisites

To run this application, you will need to have the following installed:

Python 3
Flask
Flask-Session
Werkzeug
SQLite
You will also need an API key for the IEX Cloud API. You can sign up for a free account and obtain a key from the IEX Cloud website.

Installation

Clone the repository: git clone https://github.com/cs50/finance.git
Navigate to the project directory: cd finance
Install the required packages: pip install -r requirements.txt
Set the environment variables: export API_KEY="your_iex_cloud_api_key"
Initialize the database: flask init_db
Start the application: flask run
Usage

Open a web browser and navigate to http://localhost:5000
Click the "Register" link to create a new account
Once you have registered and logged in, you can add funds to your balance, buy and sell stocks, and view your transaction history.
How it works

The finance application uses Flask, a web framework for Python, to handle user requests and render HTML templates. The application also uses SQLite, a lightweight relational database, to store user data such as account balances and transaction history.

The application integrates with the IEX Cloud API to provide real-time stock prices. When a user searches for a stock symbol, the application sends a request to the IEX Cloud API and receives a JSON response containing information about the stock, including its current price.

Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.
