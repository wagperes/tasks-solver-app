# tasks-solver-app
A simple application that makes HTTP requests to get a task and post its result.

Once the app is started, it sends a GET request to fetch a task. Then it calculates an operation (addition, subtraction, division, multiplication or remainder) and sends a POST request with the result.

The application keeps running indefinitely, fetching tasks and posting results, until a `SIGINT` (<kbd>Ctrl</kbd> + <kbd>c</kbd>) is detected.


## Application commands
* Clone the project: `git clone https://github.com/leandropaz/tasks-solver-app.git`
* Install dependencies: `npm install`
* Linter: `npm run lint`
* Run tests: `npm test`
* Run: `npm start`
