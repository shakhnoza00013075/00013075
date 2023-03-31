Medicine Registry App
The Medicine Registry App is a web application built using Node.js, Express, and Pug that allows users to review a list of available medicines and add new medicines, edit existing medicines, and delete medicines.

How to Run the App Locally
Clone this repository or download the source code.
Install Node.js if you haven't already.
Open a terminal or command prompt and navigate to the root directory of the application.
Run npm install to install the application dependencies.
Run node index.js to start the server.
Open your web browser and go to http://localhost:3000 to access the application.
Dependencies
The following dependencies are used in this application:

Express: ^4.17.1
Pug: ^3.0.2
Body-parser: ^1.19.0
Method-override: ^3.0.0
You can find the full list of dependencies in the package.json file.


The files in the Medicine Registry App are structured as follows:

node_modules/: contains all the installed dependencies.
public/: contains static files, such as CSS files.
views/: contains all the Pug templates used to render the views.
index.js: the main entry point of the application.
package.json: the configuration file for Node.js and the list of dependencies.
package-lock.json: automatically generated by npm to lock down the versions of installed dependencies.
.gitignore: a list of files and directories that should be ignored by Git.
This structure follows common conventions for Node.js applications, separating the views and static files from the server-side code for better organization and maintainability.

GitHub: 