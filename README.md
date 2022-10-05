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
11. The response.writeHead() (Added in v1..0) property is an inbuilt property of the ‘http’ module which sends a response header to the request.
12. readfile() reads data from the specified file or input/output (I/O) device.
13. nodemon <em>filename</em> helps to run a file in nodemon server.
14. A web framework (WF) or web application framework (WAF) is a software framework that is designed to support the development of web applications including web services, web resources, and web APIs. For example, many web frameworks provide libraries for database access, templating frameworks, and session management, and they often promote code reuse. The following image shows the most used web frameworks among developers worldwide, as of 2022.
15. During running your command --save, this will saves all the files but it was needed in the previous version right now it's automatically saves all the files.
  
![FrameworksImg](https://user-images.githubusercontent.com/96413187/193753936-bf883bbf-62ba-4497-a974-fa2f606182dd.PNG)

15. MVC, MVP, and MVVM are three popular design patterns in software development. MVC is one of the most frequently used industry-standard web development frameworks to create scalable and extensible projects.
16. The MVC (Model-View-Controller) is an architectural pattern that separates an application into three main logical components: the model, the view, and the controller. Each of these components are built to handle specific development aspects of an application. 
17. Express is a framework so it's a package or a set of library. And the code to install the express framework is given as <b>npm install express</b> or  <b>npm install express --save</b>. And you will receive node_modules folder within your application.
18. To fireup an express, we need to run a code of express keyword in our main file :const express = require("express"); and also a port.
19. 'utf8' is the default encoding and decoding standardization in an express.
20. A <b>template engine</b> enables you to use static template files in your application. At runtime, the template engine replaces variables in a template file with actual values, and transforms the template into an HTML file sent to the client. This approach makes it easier to design an HTML page.
21. Some popular template engines that work with Express are Pug, Mustache, and EJS. The Express application generator uses Jade as its default, but it also supports several others.
22. $ npm install ejs is the command to install ejs. Then app.set() to set the view engine and path.
23. __dirname displays the directory from which the server was started inside of a terminal.
24.  One of the keyword to send a variable value to view from a server is a locals.
25. Middleware functions are functions that have access to therequest object (req), the response object (res), and the next function in the application’s request response cycle. The next function is a function in the Express router which, when invoked, executes the middleware succeeding the current middleware.
      Code : app.use(express.urlencoded()); & Code: app.use(function(req,res,next){});
26. Middleware functions can perform the following tasks:
   <ul>
   <li> Execute any code.</li>
   <li> Make changes to the request and the response objects.</li>
   <li> End the request-response cycle.</li>
   <li> Call the next middleware in the stack.</li>
</ul>
27. To use static files in the express framework, we can type app.use(express.static(<em>staticfolderName</em>);<br/>
                                                                                                              
## Solution of a Problem Occured
Link: https://stackoverflow.com/questions/45866533/npm-install-not-creating-a-new-package-lock-json

# Documentation Links
Visual Studio Documentation : https://code.visualstudio.com/docs <br/>
Node js documentation: https://nodejs.org/docs/latest/api/process.html <br/>
Frameworks Design Explaination: https://medium.com/@ankit.sinhal/mvc-mvp-and-mvvm-design-pattern-6e169567bbad
MVC Framework Documentation Link: https://www.freecodecamp.org/news/simplified-explanation-to-mvc-5d307796df30<br/>
Project Assigned: https://ninjasfiles.s3.amazonaws.com/0000000000002059.png
EJS Docs: https://ejs.co/
Middleware Documentation Link : https://expressjs.com/en/guide/using-middleware.html

<h2>Demonstrated : </h2> 
<h4>1. process.agrv : </h4> This command returns an argument of a command line while launching a node js application. It's basically read the file of the project.
<h4>2. process.agrv.slice(2) : </h4> This command will skip the amount of arguments present inside of a javascript file.
<h4>3. parseInt() : </h4> Convert string to an integer.

//Last topic covered: My Express App : a List of contacts
