# CircleCI Pipeline

CircleCI services is set to monitor the 'main' branch within the the GitHub repository, Udagram. When updated code is pushed to the project repository via the 'main' branch, CircleCI executes the configured 'build' and 'deploy' jobs. The following events are triggered when the pushed code is detected by CircleCI.

## Workflow

### Build Job

1. Spin up environment
2. Preparing enviroment variables
3. Install Node.js
4. Checkout code
5. Install Front-End Dependencies
6. Install API Dependencies
7. Front-End Lint
8. Front-End Build
9. API Build

### Deploy Job

_Set to require success of build job_

1. Spin up environment
2. Preparing environment variables
3. Install Node.js
4. Install AWS CLI - latest
5. Configure AWS Access Key ID
6. Setting Up Elastic Beanstalk CLI
7. Checkout code
8. Deploy App
