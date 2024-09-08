
### Prerequisites

Before starting, ensure you have the following installed:
- **Node.js**: It can be downloaded from the official website. We recommend version 14.x or higher.
- **npm**: Node Package Manager (npm) comes with Node.js. Verify if it's installed by running `node -v` and `npm -v` in your terminal.

### Installation

1. Clone the repository to your local machine by running the following command:
   
   ```
   git clone https://github.com/muthu-kumar369/customerlabs-segment-test.git
   ```

2. After cloning, navigate to the project directory:
   
   ```
   cd customerlabs-segment-test
   ```

3. Install the project dependencies using npm:
   
   ```
   npm install
   ```

   This will install all the required packages listed in the `package.json` file.

### Running the Application

To run the application in development mode, use the following command:

```
npm start
```

This will start the development server on `http://localhost:3000`. You can open your browser and visit the application there. The application will automatically reload when you make changes to the source code.

### Building for Production

To create an optimized build of the application, run the following command:

```
npm run build
```

This will create a `build/` folder with production-ready static files. You can use these files for deployment to a web server.

### Additional npm Scripts

The following npm scripts are available in this project:

- `npm start`: Starts the development server.
- `npm run build`: Creates a production build.
- `npm test`: Runs the test suite.
- `npm run eject`: Exposes the app configuration for customization (use with caution as this is irreversible).

