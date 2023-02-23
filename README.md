# Price Comparison Automation Tool
This is an automation tool built with Java and Selenium that compares the regular price of products from a list with their Amazon price and notifies the user if a cheaper option is found. This tool can be run as a Chrome extension that, once enabled, runs the program.

## Installation
To install this tool, follow these steps:

Install the Java Development Kit (JDK) on your computer. You can download the JDK from Oracle's website.
Install an Integrated Development Environment (IDE) such as Eclipse or IntelliJ IDEA.
Install Selenium WebDriver for Google Chrome. You can download the WebDriver from the Selenium website.
Install Node.js and npm on your computer. You can download Node.js from the official website.

## Usage
To use this tool, follow these steps:

Clone this repository to your local machine.
Open the project in your IDE.
Import the necessary libraries, such as Apache POI, to read Excel files in Java.
Create a CSV or Excel file that contains the list of products and their regular prices.
Run the Main class to start the program.
When prompted, upload the CSV or Excel file with the list of products and their regular prices.
The program will automatically launch a new instance of Chrome and navigate to Amazon's website.
For each product in the list, the program will search for the product on Amazon and scrape its price.
The program will compare the scraped Amazon price to the regular price from the list.
If the scraped Amazon price is lower than the regular price of the product from the list, the program will send a notification to the user, for example, an email or a desktop notification.
## Chrome Extension
To run this tool as a Chrome extension, follow these steps:

Install the Node.js modules by running npm install in the chrome-extension directory.
Build the extension by running npm run build.
Open Google Chrome and go to the Extensions page (chrome://extensions).
Enable developer mode by toggling the switch on the top right.
Click on "Load unpacked" and select the build folder in the chrome-extension directory.
The extension is now installed and can be accessed by clicking on its icon in the Chrome toolbar.
When the extension is enabled, it will run the automation tool automatically.
##Credits
This project was created by Juan Maurente.

License
This project is licensed under the MIT License.



