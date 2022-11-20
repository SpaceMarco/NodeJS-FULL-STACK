# NodeJS udagram FULL-STACK application

Application [Link](http://899113371307-bucket-udagram.s3-website-us-east-1.amazonaws.com/)

## Dependencies
All packages can be found at:
> udagram/udagram-api/packages.json</br>
> udagram/udagram-frontend/packages.json </br>

## Infrastructure
this app requires the following services:

  AWS RDS for hosting postgres database</br>
  AWS S3 buckets to host the application frontend files</br>
  AWS Elastic Beanstalk (EB) to host the backend or the api for the application</br>
  CircleCI for pipelines and auto deployment</br>
  
### Steps:
    1- install all dependencies for the project.
    2- Build the project, and run it locally.
    3- Create an RDS Postgres database.
    4- Create a **PUBLIC** S3 Bucket for frontend.
    5- Create an EB enviroment for backend.
    6- Make sure that all enviroment variables are correct in EB.

## Pipeline
CircleCI tracks the main branch and pushing on the branch will:</br>
  1- install the dependencies for both frontend and backend, and build the whole project.</br></br>
  
  ![image](https://user-images.githubusercontent.com/60396165/202921293-eae2774a-aab2-4398-b38b-7c8c23901ff2.png)</br>

  2- deploy the backend and frontend on AWS.</br></br>
  
  ![image](https://user-images.githubusercontent.com/60396165/202921629-4aa536e5-4986-42c3-b6b5-cb04ba24d37b.png)

  
  ## Screenshots:
  S3 Overview</br>![image](https://user-images.githubusercontent.com/60396165/202921570-eb547de7-d9af-484a-8b9d-3ee0bfd3cba6.png)
  Elastic Beanstalk (EB)</br>![image](https://user-images.githubusercontent.com/60396165/202921740-e758b73a-937d-4d5f-a916-2b4e3f9f39e6.png)
  CircleCI enviroment variables</br>![image](https://user-images.githubusercontent.com/60396165/202921855-cb1c48f8-42c1-4585-b818-1891db6b095d.png)
  CircleCI pipeline</br>![image](https://user-images.githubusercontent.com/60396165/202921953-16ecc347-66be-45b3-9c3b-bd31240ac53f.png)



  
