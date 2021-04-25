# mern-auth-crud


##This is a Full stack Web Application where users are allowed to login/signup. Users can alsoi login with the help of google login.

**Steps**:

Clone the repo.

*Install node modules for both backend and frontend.

*Go to mongodb.com and create a new cluster and get your mongodb_uri and paste it in the .env file in server.

*Go to google developer console and create yourself a clientID in the required URL while making the client ID add the http://localhost:3000 as domain and paste that id in line82 of Auth.js in Auth folder in client folder.

*You are good to go.

*First run the server with the help of npm start.

*Then run the client with the help of npm start.


Functionalities:

When you first visit the page you'll be prompted to the login page.
Create your account and then after you are authorized you can create any post .
You can delete the post as well as edit it by clicking at  3 dots. 
Other user will then be able to see your post once they make their account and will be able to like the post but can't delete other's post.


 I then hosted the backend on heroku and the frontend on netlify.
 Everything is working fine and this is the link to the full stack application:   https://post-auth-crud.netlify.app/
