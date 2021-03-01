# DevBops

DevBops is an online social platform where developers from all around the world come together to work and socialize collectively. A platform where engineers can speak about their current projects, collab, sign up and browse events, and gain further knowledge on current projects that are in construction and deployed all around the world.

Currently, the project is working alongside AWS and other DevOps tools in order to deliver a strong and consistent app to the client. The app consists of a frontend where Flask alongside Python, HTML, CSS is used to structure the layout and what the users actually looks and interacts with. The frontend is then further connected to the API Gateway which acts as a bridge between the frontend and the backend microservices. The backend consists of codes written in Python alongside 3 microservices which are User, Events, and Blog. A well secured database is also running on DynamoDB, a database service of AWS, that is connected as the main data storage for the whole project. Alongside that, Jenkins pipeline is used to create a continuous integration of the tests that has been carried out by the QA team which is written in Python by using modules like unittest, pytest, alongside Postman.

Different tests suitable for the specific microservices are created, such as routes, creating, deleting, and updating users, checking the database, and triggering events. My team and I used implemented Jenkins which is being used for CI/CD methodology as it helps us greatly to not only automate the tests running for the microservices but also providing troubleshooting locations if needed for any sudden crashes.

Furthermore, for automation purposes, Docker is being used for image building and deployment.

The entire project is currently running in agile methodology and is communicated via Jira on a daily to weekly basis.
