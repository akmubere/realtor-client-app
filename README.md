# realtor-client-app


# Firefly
[!Codeship Status for codeship/documentation]

## Core Libraries

React v15
* Redux - All state is stored in a single store
* React Redux Form (RRF) - Manages all input fields and links them to the store
* Material UI - A set of pre-built components which adhere to Google's Material UI guidelines
* React Router - Routing library which keeps track of the URL.

## Development Server

### Run
npm start
Open browser and navigate to http://localhost:9001

### URL Flags
The application looks for the following flags on startup:

**portal_id** (Required): The portal ID to use when fetching theme and borrower information.
**hideTitleBar** (Optional): If true the title bar will be hidden. Used when embedding this application inside a portal.
Example of both used together:

'http://localhost:9001?portalID=123456&hideTitleBar=true'


# Unit Testing
###  Run

* All Specs:
npm test

* Live Watching
npm test -- --watch
This will run Jest in watch mode. Any file changes will automatically re-run the tests.

* Single Spec:
**npm test -- --watch
This will run all tests by default. Use the shortcuts shown by Jest to filter individual files

### Tools
This app uses Jest for unit tests

### Linting
To check the code base for linting errors/warnings (there should be none):

npm run lint

### JavaScript
This app uses ESLint to check the code for consistency and potential errors. Ensure that your editor has the appropriate ESLint plugin (it should automatically pick up the configuration in .eslintrc). For a list of rules see the shared config: https://github.com/BOA-Restrictor/eslint-config-lendesk/blob/master/index.js

### Styles (CSS & SCSS)
This app uses ____ to check CSS/SCSS stylesheets. See the Stylelint editor plugins page for a list for most common editors. The command npm run lint will include linting all stylesheets.
