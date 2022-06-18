# Hosting a Full-Stack Application

# Udagram

You can find the completed project [here](http://udagram-project-fe.s3-website-us-west-2.amazonaws.com/home).

---

The project has been provided for by Udacity. This capstone project is meant to familiarize and practice provisioning and configuring several AWS services to develop a Full-Stack JS application. The included services are:

- AWS S3 (web hosting and media upload)
- AWS RDS PostgreSQL Database
- AWS Elastic Beanstalk environment configuration

CircleCI is also used to create a pipeline for streamlined development by implementing CI/CD practices. CircleCI is configured to monitor the project via GitHub and trigger the workflow when new code is pushed.

### Installation

Ensure that you are in the project root directory.

1. `npm run frontend:install && npm run api:install`
2. Open the terminal, run `npm run api:start`.
3. In a seperate terminal window/tab, run `npm run frontend:start`.
4. Once the front-end is successfully compiled and the project is connected to the database, open the browser at localhost:4200 to view the project.

In order to successfully run the application locally, you must create a .env file and set the proper environment variables.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
