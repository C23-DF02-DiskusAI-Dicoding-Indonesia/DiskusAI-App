# DiskusAI-App
This is a DiskusAI-App front-end application designed to showcase the capabilities of Chatbot serving and Search bar serving APIs. The app, powered by Node.js and Express, allows users to explore the various features offered by each API and their seamless integration. It acts as a consumer of APIs from external websites, leveraging CORS support to facilitate secure communication between the app and the APIs.

To run the app, follow these steps:

*  Make sure you have Node.js installed on your system. You can download it from the official Node.js website (https://nodejs.org) and follow the installation instructions for your operating system.

*  Create a new directory for your project and navigate to it in your terminal or command prompt.

*  Copy the code you provided and save it in a file named app.js within your project directory.

*  Open a terminal or command prompt and navigate to your project directory.

*  Run the following command to install the required dependencies:

```bash
npm install express
```
This will install the Express framework.

*  Once the dependencies are installed, you can start the server by running the following command:

```bash
node app.js
```

You should see a message indicating that the server is running on http://localhost:4000.

*  Open a web browser and visit http://localhost:4000 to access the main page of your app.

You should now be able to navigate to different routes such as /chatbot, /searchbar, and /integrated to access the corresponding HTML files.

Note: Make sure you have the necessary HTML files (index.html, chatbot.html, searchbar.html, integrated.html) in the same directory as your app.js file, or adjust the file paths accordingly in your code.
