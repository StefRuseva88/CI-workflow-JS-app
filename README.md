# CI workflow for "Student Registry" Node.js App
## This is a test project for **Back-End Test Automation** March 2024 Course @ SoftUni
![image](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![image](https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![image](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

---
### Overview
This repository contains a Node.js app. The project focuses on building a CI workflow using GitHub Actions to automate testing of a pre-existing Node.js application ("Student Registry").

### Project Goals:

- Implement a CI workflow in GitHub Actions.
- Configure the workflow to run tests on the "Student Registry" application.
- Test the application using multiple Node.js versions.

### Prerequisites:

- Basic understanding of Node.js and testing frameworks.
- Familiarity with GitHub Actions.
  
### Setup:

- Clone this repository.
- Install dependencies and run the application:
  
  ``` sh
  npm install
  npm start
  ```
  
- Review the existing "Student Registry" application code.
  
### Running Tests:

The CI workflow is already defined in the `.github/workflows` directory. Pushing your code to the main branch will trigger the workflow automatically. The workflow will:

- Set up the environment.
- Install dependencies.
- Run tests for the "Student Registry" application on two different Node.js versions.
### Additional Notes:

- This project serves as a demonstration of CI/CD concepts using a pre-existing application.
- The specific details of the "Student Registry" application are not covered in this repository.

### Contributing
Contributions are welcome! If you have any improvements or bug fixes, feel free to open a pull request.

### License
This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.

### Contact
For any questions or suggestions, please open an issue in the repository.
