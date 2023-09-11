# House_Bidding_website
House_bidding

House_bidding is a web application that simulates a bidding process for houses. The application allows users to register, log in, and bid on houses. The highest bidder wins the auction for a house once the bidding period ends.
Installation

To run the House_bidding application locally, you need to have Node.js and npm installed on your machine. You also need to have a MongoDB instance running. Once you have these installed, follow these steps:

    Clone the repository to your local machine.
    Navigate to the root directory of the project in your terminal.
    Run npm install to install the dependencies.
    Create a .env file in the root directory of the project with the following contents:

c

MONGODB_URI=<your MongoDB connection string>
JWT_SECRET=<a secret string for JWT authentication>

    Run npm run dev to start the application in development mode.
    Open a web browser and navigate to http://localhost:3000.

Usage

The House_bidding application provides a simple user interface with a list of available houses on the home page. Clicking on a house displays detailed information about the house, including the current highest bid and the bidding period.

To bid on a house, users need to register and log in to the application. Once logged in, they can enter their bid amount in the input field and submit the bid. The application uses Socket.IO to display real-time updates of the current highest bid.

The highest bidder wins the auction for a house once the bidding period ends. The application then displays a message with the winner's name and bid amount.
Contributing

If you would like to contribute to the House_bidding project, feel free to fork the repository and submit a pull request. Please make sure to follow the code style and formatting conventions used in the project.
License

House_bidding is licensed under the MIT License.
