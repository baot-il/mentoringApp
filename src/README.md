## MENTORS-FRONTEND

### Environemnt Setup
#### Install dependencies 
 * npm
 
#### Config local firebase
 1. Create a project in firebase using this link (might take a few minutes) https://console.firebase.google.com/u/0/?pli=1
 2. Go to Develop Tab -> Authentication and click on the set up sign-in method button
 3. Edit Email/Password option and enable the first option, sign by email.
 4. Go to project settings -> Your Apps card -> select web app platform (</> icon)
 5. Choose a nice nickname, no need to check the checkbox and click on register button.
 6. You **don't** need to copy the SDK snippet
 7. In your project the root project folder creat a text file named .env
 8. Set the following variables with the generated key from firebase:
    ```
    REACT_APP_API_KEY=[REPLACE_WITH_YOUR_API_KEY]
    REACT_APP_AUTH_DOMAIN=[REPLACE_WITH_YOUR_AUTH_DOMAIN]
    REACT_APP_PROJECT_ID=[REPLACE_WITH_YOUR_PROJECT_ID]
    REACT_APP_APP_ID=[REPLACE_WITH_YOUR_APP_ID]
    ```

### Configuring API url
Currently you will need to work with a local backend. Please follow the instructions:  https://github.com/baot-il/mentors-backend

Once you have running local backend please add the following var:
REACT_APP_ENV=http://localhost:5000

IF YOU ARE WORKING WITH A PROD / STAGING env you should change the values. 
```
// PRODUCTION https://baot-mentors-prod.herokuapp.com
// STAGING https://baot-mentors-stage.herokuapp.com
// LOCALHOST localhost:5000
```

### Project Setup
* run ```npm install```

### Run Project
* npm start 

