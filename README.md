# Label-Sensoring-Checks-
Description: Intake a JSON file of label annotations and check against annotation values for possible flags.

Usage:
In order to properly use this tool, you will need to download the project as a zip or clone into the repositiory. 
Once downloaded you can run a simple server from your terminal. The easiest way to do so would be by using NPM.
If you dont have NPM installed you can type the following command in your terminal or command prompt:

  npm install npm@latest -g

after npm is installed, run the following command:

  npm install --global http-server

Once the http-server has downloaded you can run the folder on a server. Make sure youre in the folder of the project and run:

  http-server -c-1
  
After this command is run, click on the server url provided: http://127.0.0.1:8080, and click on the process.html file to run
the script on the included JSON file in the folder. Once run, the page will output a CSV file of potential flags on task annotations. 
Make sure you enable downloads if requested by site's settings. This script has been designed to specifically intake the tasks.json file,
however in the future would be improved by allolwing the user to upload any chosen JSON or other type of format file and adjust
the quality checks through some UI/UX experience. While this project is no where near production standard. It is an outline of how 
one could potentially injest data, analyze that data, and output in a downloadable form all from a web applciation.
