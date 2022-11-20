# Infrastructure:
this app requires the following services:</br>

    AWS RDS for hosting postgres database</br>
    AWS S3 buckets to host the application frontend files</br>
    AWS Elastic Beanstalk (EB) to host the backend or the api for the application</br>
    CircleCI for pipelines and auto deployment</br>

## Steps:
    1- install all dependencies for the project.</br>
    2- Build the project, and run it locally.</br>
    3- Create an RDS Postgres database.</br>
    4- Create a **PUBLIC** S3 Bucket for frontend.</br>
    5- Create an EB enviroment for backend.</br>
    6- Make sure that all enviroment variables are correct in EB.</br>