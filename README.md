**An nginx-like http server built using expressJS, using the NodeJS runtime environment**

- Import Postman docs from `ExpressJS_server.postman_collection.json` to explore functionality and requests served by server
- Create a .env file in root directory to use dotenv to set port number by inserting the following text into the .env file:
  `PORT=<port number to listen on>`
- Use `npm run start` to start the server
- This project uses ExpressJS to create a server that responds to http requests on the port specified in the .env file and performs basic crud operations
- All data is stored in a in memory database so is volatile in nature. DON'T STORE IRRETRIVABLE DATA USING THIS UTILITY
- Uses winston and morgan to log all relevant activity to `src/app.log` and prints relevant info on activity to the server's console
- Have fun modifying the src as you wish! You can fork this repo and fetch this codebase to your work environment using git on your machine
- Thank you! this is my first time writing documentation for a project other than using Postman. If you have any advice for me in regards to anything, reach out to me on github or you can open an issue on any of my repositories. Have a good day!
