<<<<<<< HEAD
# Containerized-Dream-Vacation-App1

## Frontend/Dockerfile
![Screenshot](https://github.com/CreatorObinna-byte/Containerized-Dream-Vacation-App1/blob/edcf8610e22378605d0fe1d611a4e09bb38ff8ef/Screenshot%20From%202025-07-18%2018-26-37.png))


## Backend/Dockerfile
![Screenshot](https://github.com/CreatorObinna-byte/Containerized-Dream-Vacation-App1/blob/bb0b6b7eeedc78c5b191ebf15d59d6e1d2ddfbe9/Screenshot%20From%202025-07-18%2018-28-24.png))

## Docker-compose.yml
![Screenshot](https://github.com/CreatorObinna-byte/Containerized-Dream-Vacation-App1/blob/9ec9c25c09a52c2340fccfd0c6fdf651ea1428f1/Screenshot%20From%202025-07-18%2018-31-34.png)
![Screenshot](https://github.com/CreatorObinna-byte/Containerized-Dream-Vacation-App1/blob/23c7793d9e71a0735a165f55d12e5ca322dd2d68/Screenshot%20From%202025-07-18%2018-32-02.png)

![Screenshot](https://github.com/CreatorObinna-byte/Containerized-Dream-Vacation-App1/blob/97ccb5df1045ead2eab6f3ed435fb3fa49a9238b/Screenshot%20From%202025-07-18%2020-25-06.png)
![Screenshot](https://github.com/CreatorObinna-byte/Containerized-Dream-Vacation-App1/blob/9ae0c2d8acf9ab2b1e4c6bd69483ebf3c1152a73/Screenshot%20From%202025-07-19%2014-32-59.png)
![Screenshot](https://github.com/CreatorObinna-byte/Containerized-Dream-Vacation-App1/blob/576934be989b4107618d509ad442005a09fbd2bf/Screenshot%20From%202025-07-19%2014-41-03.png)

## README.md
![Screenshot](https://github.com/CreatorObinna-byte/Containerized-Dream-Vacation-App1/blob/4f03ce09d9f220a84d2cc2db53998469259d9e92/Screenshot%20From%202025-07-19%2021-04-37.png)
![Screenshot](https://github.com/CreatorObinna-byte/Containerized-Dream-Vacation-App1/blob/c8eb10b1506c8a413802bad7bdbb396d373c55e2/Screenshot%20From%202025-07-19%2021-05-33.png)
=======
# Dream Vacation Destinations

This application allows users to create a list of countries they'd like to visit, providing basic information about each country. The project is structured to mimic a real-life production environment, employing best practices in software development, deployment, and continuous integration/continuous delivery (CI/CD).

## Setup

### Backend
1. Navigate to the `backend` directory.
2. Run `npm install` to install dependencies.
3. Set up your PostgreSQL database and update the `.env` file with your database URL.
4. Run `npm start` to start the server.

### Frontend
1. Navigate to the `frontend` directory.
2. Run `npm install` to install dependencies.
3. Update the `.env` file with your API URL (e.g., `REACT_APP_API_URL=http://localhost:3001`).
4. Run `npm start` to start the React development server.

## Features
- **Add Countries**: Users can add countries to their dream vacation list.
- **View Country Details**: Displays capital, population, and region information for each country.
- **Remove Countries**: Users can remove countries from their list.
- **Production-Ready Setup**: The project is designed to be scalable and maintainable, following industry-standard practices for deployment and CI/CD.

## Roadmap
- **CI/CD Implementation**: Automate the build, test, and deployment process using industry-standard CI/CD tools.
- **Infrastructure as Code (IaC)**: Implement IaC for automated environment setup and management.
- **Scalability**: Enhance the application to support multiple environments (staging, production) with proper domain names and configurations.
- **Security**: Utilize Kubernetes Secrets and environment variables for secure data management.
- **Microservices**: Modularize the application into microservices to improve maintainability and scalability.

## Technologies Used
<<<<<<< HEAD
- Frontend: React
- Backend: Node.js with Express
- Database: PostgreSQL
- External API: REST Countries API
>>>>>>> 1a73ed5f (first commit)
=======
- **Frontend**: React
- **Backend**: Node.js with Express
- **Database**: PostgreSQL
- **External API**: REST Countries API
- **CI/CD**: To be implemented with [CI/CD tools, e.g., GitHub Actions, Jenkins, or Azure DevOps]
- **Infrastructure as Code**: To be implemented with tools like Terraform or Helm

## Best Practices
- **Version Control**: All changes are tracked in Git for collaboration and history management.
- **Environment Management**: Separate configurations for different environments (development, staging, production) using environment variables.
- **Security**: Sensitive information is managed using environment variables and Kubernetes Secrets.
- **Documentation**: The project is well-documented to facilitate onboarding and maintenance.
>>>>>>> 81787e3b (modified Readme.md)
