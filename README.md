# GithubActions_Project_20

This project is a coding quiz application built with a React frontend and an Express/MongoDB backend. The purpose of this project was to implement and enhance testing for the existing codebase, ensuring the application is robust and reliable.

## Features
- **Frontend**: Built with React, utilizing Bootstrap for styling.
- **Backend**: Powered by Express and MongoDB, with Mongoose for database modeling.
- **Testing**: Comprehensive testing using Cypress for end-to-end and component tests.
- **GitHub Actions**: Automated workflows for testing and deployment.

## Project Structure
- **Client**: Contains the React frontend.
- **Server**: Contains the Express backend and MongoDB configuration.
- **Cypress**: Includes test files and configurations for end-to-end and component testing.

## Testing Highlights
- **Component Testing**: Cypress is used to test individual React components, ensuring they behave as expected.
- **End-to-End Testing**: Cypress tests simulate user interactions to verify the application works as a whole.
- **Mocking API Calls**: Mock data is used in tests to isolate the frontend from the backend.

## GitHub Actions
- **Test Workflow**: Automatically runs tests on pull requests to the `develop` branch.

![image](https://github.com/user-attachments/assets/aba6e043-0090-4f54-8097-8fadd659ae8a)


- **Deploy Workflow**: Deploys the application to a hosting service when changes are pushed to the `main` branch.

  Deployed to Render: https://githubactions-project-20.onrender.com

## How to Run the Project
1. Clone the repository.
2. Install dependencies:
   ```bash
   npm run install
   ```
3. Start the development environment:
   ```bash
   npm run develop
   ```
4. Run tests:
   ```bash
   npm run test
   ```

## License
This project is licensed under the MIT License. See the LICENSE file for details.
