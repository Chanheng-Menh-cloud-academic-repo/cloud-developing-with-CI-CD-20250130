# cloud-developing-with-CI-CD-20250103
## Assignment 2 - Run NodeJS Web Server on EC2 and View from your Browser
<br><br>
### Submission PROCESS

Select SANDBOX to perform your task. AFTER FINISH YOUR WORK, YOU SHOULD DO LOGOUT AND END LAB.

TAKE THE SCREEN SHOT OF EACH STEPS.

PASTE IT IN WORD DOCUMENT.
Convert it into a single PDF file. 
You can use this website for conversion - https://www.ilovepdf.com/jpg_to_pdf
THEN UPLOAD that single pdf file in Canvas.

In NodeJS Server you can use http server which is the default server available or You can use the Express Server also [code will be different for express server]


<br><br>

**You can use the following code for index.js file or you can use your own code.**

var http = require('http');

//create a server object:

http.createServer(function (req, res) {

  res.write('I am Learning Cloud Developing'); //write a response to the client
  
  res.end(); //end the response
  
}).listen(80); //the server object listens on port 80


<br><br>

### ASSIGNMENT :

1. CREATE AN EC2 INSTANCE (SELECT Ubuntu/Amazon) IN AWS.

2. CONNECT IT FROM YOUR LAPTOP USING PUTTY/TERMINAL.

3. UPDATE OS - *Screen Shot*.

4. INSTALL NodeJS and npm - *Screen Shot*.

5. Github:



    a. Create Github Account - *Screen Shot*.

    b. Create a repository - *Screen Shot*.

    c. Push / Upload your NodeJS Project / code in the github - *Screen Shot*.

6. Install Git on the EC2 instance - *Screen Shot*.

7. Clone your code from Github to EC2 instance - *Screen Shot*.

8. Run your NodeJS code - *Screen Shot*.

9. Access it from your Laptop browser using EC2 Public IP - *Screen Shot*.

### YOU NEED TO DO SOME RESEARCH WORK.
