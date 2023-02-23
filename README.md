# Price Comparison Automation Tool
This is an automation tool built with Java and Selenium that compares the regular price of products from a list with their Amazon price and notifies the user if a cheaper option is found. This tool can be run as a Chrome extension that, once enabled, runs the program (still in production).

## Installation
To install this tool, follow these steps:

1. Install the Java Development Kit (JDK) on your computer. You can download the JDK from Oracle's website.
2. Install an Integrated Development Environment (IDE) such as Eclipse or IntelliJ IDEA.
3. Install Selenium WebDriver for Google Chrome. You can download the WebDriver from the Selenium website.
4. Install Node.js and npm on your computer. You can download Node.js from the official website.

## Usage
To use this tool, follow these steps:

1. Clone this repository to your local machine.
2. Open the project in your IDE.
3. Import the necessary libraries, such as Apache POI, to read Excel files in Java.
4. Create a CSV or Excel file that contains the list of products and their regular prices.
5. Run the Main class to start the program.
6. When prompted, upload the CSV or Excel file with the list of products and their regular prices.
7. The program will automatically launch a new instance of Chrome and navigate to Amazon's website.
8. For each product in the list, the program will search for the product on Amazon and scrape its price.
9. The program will compare the scraped Amazon price to the regular price from the list.
10. If the scraped Amazon price is lower than the regular price of the product from the list, the program will send a notification to the user, for example, an email or a desktop notification.

## Chrome Extension (to be built soon)
To run this tool as a Chrome extension, follow these steps:

1. Install the Node.js modules by running npm install in the chrome-extension directory.
2. Build the extension by running npm run build.
3. Open Google Chrome and go to the Extensions page (chrome://extensions).
4. Enable developer mode by toggling the switch on the top right.
5. Click on "Load unpacked" and select the build folder in the chrome-extension directory.
6. The extension is now installed and can be accessed by clicking on its icon in the Chrome toolbar.
7. When the extension is enabled, it will run the automation tool automatically.
## Credits
This project was created by Juan Maurente.

## License
This project is licensed under the MIT License.



