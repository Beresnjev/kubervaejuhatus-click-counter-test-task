# Click Counter Angular Application

## Prerequisites

Before starting, make sure you have the following tools installed:

- **Node.js**: Version 16 or higher (Angular CLI expects a Node.js LTS version). You can check your version by running:
```bash
node -v
 ```

- Yarn: A package manager used for this project. Install it globally by running:
```bash
npm install -g yarn
```

- Angular CLI: Required to run the Angular app using ng serve. Install it globally with:
```bash
npm install -g @angular/cli
```

## UI installation

Follow these steps to install and run the application:

1. Clone the repository: Clone the project repository to your local machine:
```bash
git clone <repository_url>
cd click-counter-app
```

2. Install dependencies: Once you're in the project directory, run the following command to install all the required dependencies:
```bash
yarn install
```

3. Install Angular app dependencies: Navigate to the Angular project directory, then install dependencies using:
```bash
cd ui/click-counter-app
npm install
```

4. Running the Application

After the installation is complete, you can run the Angular application using the following steps:

Start the development server: To start the app in development mode, navigate to angular app directory and run:
```bash
ng serve
```

This will compile the application and serve it locally. By default, the app will be available at:
```
http://localhost:4200
```

Open the application in your browser: Once the server is running, open your browser and go to http://localhost:4200. 
You should see the "Click Counter" UI with a button that increments the count on each click.

## Running Tests
To run tests on your application, make sure the app is running locally. Then you can execute the tests:

- On Linux/macOS:
Set the PAGE_URL environment variable: Run the following command (replacing http://localhost:4200 with the actual URL where the application is running):
```bash
PAGE_URL="http://localhost:4200" yarn test
```

- On Windows (Command Prompt):
Set the PAGE_URL environment variable: Run the following command (replace http://localhost:4200 with the actual URL):
```cmd
setx PAGE_URL "http://localhost:4200"
yarn test
```
