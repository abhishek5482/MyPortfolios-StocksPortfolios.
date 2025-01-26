My Portfolios is a site that helps you track and monitor multiple stock portfolios in real-time. You can simply add the stocks that you want to monitor and you will get updated statistics about your portfolio performance (gains, market values, dividends and more.

Steps to run Program:

Navigate to the Project Directory:
Open the folder where you downloaded the project files. Inside the main folder, you will find separate directories for the frontend (client) and the backend (server).

Install Dependencies:

Set Up Environment Variables:

In the backend directory (server), create a new file named .env.
Inside the .env file, define necessary variables, such as the port number, database connection string, and stock API key.
For example:
A MongoDB connection string to store your stock data.
An API key to fetch real-time stock prices.
Start the Backend Server:
Run the backend server to handle data storage, API calls, and business logic. Make sure your MongoDB instance is running, and the connection string is correctly configured.

Start the Frontend Application:
Open a separate terminal window and navigate to the frontend directory (client). Start the development server for the frontend to display the user interface in the browser.

Open the Website in a Browser:
After both the frontend and backend servers are running, open your browser and navigate to http://localhost:3000 (or the port configured in your environment) to access the application.




Assumptions or Limitations
Real-Time Data: The application relies on a stock price API. Ensure your API key has sufficient quota for frequent requests.
Supported Stocks: Only stocks available via the integrated API can be added to the portfolio.
Database Dependency: Requires MongoDB to be set up and accessible.
Single User: If user authentication is not implemented, it assumes one portfolio per deployment.
Data Accuracy: Stock prices may have slight delays based on the API service provider.


![demo](https://github.com/user-attachments/assets/0abba4ae-1699-4966-831f-3ad247b52711)
