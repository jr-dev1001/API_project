# shapeAi_project_cybersec
This is for shapeAI cybeersecurity project.
Here we are mainly concentrating on the concept of API(Application Programming interface).
API works between client and the server.
There are few types of APIs.
  1.REST APIs -3rd party API
  2.SOAP APIs
  3.GRAPHQLs- This is developed by facebook.
  4.ASP.NET
This project includes using REST API.
API takes the request from the client and give it to server and then server response will be given to the client again.
API won't give the complete access to the server it will be very limited and everthing will be monitered.
It's done by API key it is like a secret code.
This API key uses tracks & moniter ,limiting the number of requests and security purpose.
In this project we use weather API.
We have some RESPONSE CODES:
          200-299 :- successful requests
          300-399 :- Redirections
          400-499 :- Client side errors
              404 :- Not Found
              403 :- Forbidden
          500-599 :- Server side errors
And the code explains the data we requested from the server for wheather focast data and how we've retrive the data by using python.
In this we import the request module to get a response from the server.
And we are reading the into a text file using pyhton file handling concept.
That's the text file is a demo wheather the code is reading and writing it in a text file.
