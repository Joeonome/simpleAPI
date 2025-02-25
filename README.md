# simpleAPI

(API endpoint: https://simple-api-41uu.vercel.app/)

Description:
  A Simple API Call to return a JSON Object
  (https://github.com/Joeonome/hng12-stage0-simpleAPI.git)

How to Setup:
  - clone repo with command: "git clone https://github.com/Joeonome/hng12-stage0-simpleAPI.git" to your desired directory
  - install the necessary dependencies to the folder in "./api/index.js" file
  - run "node ." in terminal
  - go to "http://localhost:8080/" to check that app is runnung
  - use API testing platforms like postman to verify other details like status code, response time, etc


Endpoint URL = https://simple-api-41uu.vercel.app/

Request/response format = JSON

Response code = 200

Example usage: 

Define the API URL

  ```
const apiUrl = 'https://simple-api-41uu.vercel.app';

```

 Make a GET request

```
fetch(apiUrl)
  .then(response => {
    if (!response.ok) {
      throw new Error('Network response was not ok');
    }
    return response.json();
  })
  .then(data => {
    console.log(data);
  })
  .catch(error => {
    console.error('Error:', error);
  });
```
  
Contact: 

    email: joseph.onumeguolor@gmail.com
    repo-url:[ https://https://github.com/Joeonome/
    
Server:

    url: https://vercel.com/
    
Tags:

    name: simpleAPI
    
    description: Returns an e-mail, date_time & git repo in json format

HNG: https://hng.tech/hire/nodejs-developers
