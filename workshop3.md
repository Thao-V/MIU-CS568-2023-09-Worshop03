# Workshop 3: Added context to WS2
## Following the previous workshop, you can copy the project to this directory (please do not copy node_modules since it is automatically created by running the command `npm install`)
## Copy the file `network.js` into your application
## Implement the component `Login` containing the following features.
1. Email Input: Users can enter an email by using this input
2. Password Input: Users can enter the password here
3. Login Button: When clicking on the button, use the function `login` in the file `network.js` to check if the email and password are correct. If so, navigate to the Home page. Otherwise, just alert the error.
## Implement the Home page in the previous workshop again to cooperate with the Login component
1. Users only access this component if they log in successfully
2. Use Context to keep the global data
3. Use function `getTasks` in the file `network.js` to initialize the list of tasks.
## Style your app using the regular CSS
## Please submit this workshop by 2:00 PM today