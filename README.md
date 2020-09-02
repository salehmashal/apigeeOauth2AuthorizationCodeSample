login-app node.js
========

***Prerequests***

- node js and npm installed on your machine.

- An apigee account (You can use apigee free trial for this demo).

- Complied OAuth2.0 API Proxy deployed to your apigee org.



**How to use:**

        1- Change the config/config.js file parameters:


                url: your apigee endpoint


                basicToken: Basic Token for the login app


                host: The URL to the login app


                port: The port login app published on


        2- Run `npm install`


        3- node app.js
