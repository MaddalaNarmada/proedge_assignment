# proedge_assignment

Given Task

A frontend which accepts a comma separated list of roll numbers (front end must be in React or Nextjs)

On entering the value and pressing submit, a request should be sent to the backend (write a backend API in nodejs to accept this from frontend)

From the backend, you have to call an external API to get the pass/fail result, as follows: http://proedge.me/test.php?rollnumber=123

In the above, rollnumber is the value to be passed, and it will return pass or fail results. This external API only accepts 1 rollnumber per call.

From the backend, when all the rollnumber results are known, return the results to the frontend

On frontend, display the roll numbers and their result in a tabular format.


Installation
Run the server npm start The server is running at localhost:3000



![edge1](https://user-images.githubusercontent.com/63226048/120914810-139bde00-c6be-11eb-930c-de086c106f90.png)

Components of code
This is the homepage which consists of the form through which we will pass the values to the API.


Test-Cases
for this input: 5,6,9,12,18,20,25,30,32,36,37,38,40,42,45,47,49,50

![edge3](https://user-images.githubusercontent.com/63226048/120914957-c5d3a580-c6be-11eb-95f9-1ccc99a2d2db.png)

Result

![edge4](https://user-images.githubusercontent.com/63226048/120914991-f61b4400-c6be-11eb-9c39-c1c8013f32de.png)


Libraries and Plugins
Node.js Expressjs Pug body-parser node-fetch









