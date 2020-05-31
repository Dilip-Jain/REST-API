Q: Create a personal website using full-stack development which uses a REST API to tell system date and time by an API call.
The website should work on the localhost.

Date and Time is the website created by Dilip Jain using full-stack development which uses REST API.
The front-end of the website involves a index.html along with style.css and script.js for design and workflow.
The back-end of the website uses node.js (app.js) in order to create a local server @port 3000. It includes express, cors and body-parser.

Using the GET method (http methods), I create a JSON at link localhost:3000/time, which is retrieved by the front-end using Fetch API's default GET method. 
The response is parsed as JSON and showed on the webpage as a string.




HOW TO USE:
1. Intall node js and all the required dependencies using npm install.
2. In the root directory place, app.js and the public folder.
        a. Public folder includes index.html, style.css, script.js, iphone.png and crop.jpg
3. To start the server, run node app.js command in the node terminal.
4. The terminal shows Server Started at port: 3000.
5. On your browser, search for localhost:3000/
6. That's it.




NOTE: if index.html (in public directory) is viewed directly without starting the server, it won't fetch the data from server thus throwing an error (check: browser 
console). This error will be catched by catch and it's function would execute, which is capable of showing date and time without backend, simply using Date() object 
in JavaScript.

Thanks.