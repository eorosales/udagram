# Infrastructure

Udagram
    /udagram-frontend
    /udagram-api

## Udagram Application Project

Udagram project provisions several AWS cloud services to host and serve all necessary components for the application. The following services are utilized:

### Front-End

/udagram-frontend

- Angular single page application framework
- AWS S3 dedicated bucket configured for public hosting
- AWS S3 dedicated bucket configured for user submitted media

### Back-End API

/udagram-api

- Express for minimal and flexible Node API framework
- AWS Elastic Beanstalk configured Node runtime environment
- AWS RDS database for storing user info
- PostgreSQL engine as stable database management system
