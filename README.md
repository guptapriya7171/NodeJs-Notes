# NodeJs-Notes
Programmers use this stack to develop web apps. They also use it to develop mobile apps.

## Practically Done
1. There are two popular stacks in full stack developement which is MEAN and MERN.
2. MEAN is a highly popular technology stack, and it’s a full-stack. 
“MEAN” is an abbreviation and the letters stand for MongoDB, Express.js, Angular, and Node.js, respectively.
3. MERN is another open-source technology stack, and you can categorize this too as full-stack. The abbreviation MERN stands for MongoDB-Express.js-React-Node.js, and you can create web and hybrid mobile apps with it.<br/>
4. Module: Module is a set of library or reusable code.
5. npm init - Helps to create a server and provide a structure to the project. Hence make a required configuration.
   npm install -g nodemon - The code helps to Install Nodemon In Windows 
6. fs - fs stand for file system. It's a module used to read and write file build into node js.
7. To use the HTTP server and client one must require('node:http').
8. The http.createServer() method turns your computer into an HTTP server.
9. app.get() is a function that tells the server what to do when a get request at the given route is called. 
   It has a callback function (req, res) that listen to the incoming request req object and respond accordingly using res response object.
   Both req and res are made available to us by the Express framework.
10. Port keyword allows you to dynamically set the listening port using what are called "environment variables".
11. writeHead() asynchronous inbuild function to read a file.
12. readfile() reads data from the specified file or input/output (I/O) device.
13. nodemon <em>filename</em> helps to run a file in nodemon server.
14. A web framework (WF) or web application framework (WAF) is a software framework that is designed to support the development of web applications including web services, web resources, and web APIs. For example, many web frameworks provide libraries for database access, templating frameworks, and session management, and they often promote code reuse. The following image shows the most used web frameworks among developers worldwide, as of 2022
  
![FrameworksImg](https://user-images.githubusercontent.com/96413187/193753936-bf883bbf-62ba-4497-a974-fa2f606182dd.PNG)

## Solution of a Problem Occured
Link: https://stackoverflow.com/questions/45866533/npm-install-not-creating-a-new-package-lock-json

# Documentation Links
Visual Studio Documentation : https://code.visualstudio.com/docs <br/>
Node js documentation: https://nodejs.org/docs/latest/api/process.html <br/>
Project Assigned: https://ninjasfiles.s3.amazonaws.com/0000000000002059.png

<h2>Demonstrated : </h2> 
<h4>1. process.agrv : </h4> This command returns an argument of a command line while launching a node js application. It's basically read the file of the project.
<h4>2. process.agrv.slice(2) : </h4> This command will skip the amount of arguments present inside of a javascript file.
<h4>3. parseInt() : </h4> Convert string to an integer.
