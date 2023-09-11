# Full Stack Apps on AWS Project

You have been hired as a software engineer to develop an application that will help the FBI find missing people. The application will upload images to the FBI cloud database hosted in AWS. This will allow the FBI to run facial recognition software on the images to detect a match. You will be developing a NodeJS server and deploying it on AWS Elastic Beanstalk.
You will build upon the application we've developed during the lessons in this course. You'll complete a REST API endpoint in a backend service that processes incoming image URLs.

## Getting Started

You can clone this repo to run the project locally, or navigate to the workspace in the Udacity course.

## Project Instructions

To complete this project, you will need to:

- Set up node environment
- Create a new endpoint in the server.js file
- Deploying your system

## Testing

Successful URL responses should have a 200 code: http://projectstartercode-dev2.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://statusneo.com/wp-content/uploads/2023/02/MicrosoftTeams-image551ad57e01403f080a9df51975ac40b6efba82553c323a742b42b1c71c1e45f1.jpg
Ensure that you include error codes for the scenario that someone uploads something other than an image: http://projectstartercode-dev2.us-east-1.elasticbeanstalk.com/filteredimage?image_url=xyz
and for other common errors: http://projectstartercode-dev2.us-east-1.elasticbeanstalk.com/filteredimage?image_url=

## License

[License](LICENSE.txt)
