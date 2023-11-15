A functional calculator coded with JavaScript. The user can perform operations of +, -, * and / with intigers or rational numbers. It also has the buttons of DEL to delete and AC to clear.
To practice end to end testing i used cypress. I performed some simple tests of clicks to check if the outputs were what was expected.


To run the application you can use --> npm start                                this will open in a 8080 port by default
To run the tests execute the command --> npm test --port 8080                   or change the port value with the desired port
If you run the application with open live server then the port might be different, hence you need to change the --port number to run the tests

If the localhost or server is on a different port, you need to change the baseUrl value with that port in the cypress.config.js file

Make OBS recording