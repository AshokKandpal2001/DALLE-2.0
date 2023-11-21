# Project Title
DALLE 2.0

## Overview

This project is build using OPEN AI API KEY. It uses OPEN AI Dalle image generation model to generate images based on user entered prompt.

## Technologies Used

- Tailwind CSS: Tailwind CSS is used for styling to increase the user experience.
- React: Front end is build using React JS for user experience so that user can interact with the application
- Cloudinary: To upload user previously generated images on cloud Cloudinary is used.
- MongoDB: User data, Post and prompts are stored on Mongo DB.

## Usage

### Prerequisites

Users need to have the following APIs and keys ready before using the project:

- OpenAI API Key: Users must obtain their OpenAI API key from https://platform.openai.com/api-keys.
- Cloudinary API Key: Go to cloudinary.com and sign-up. After Creating your account go to dashboard and there you will find your Cloud Name , Cloudinary API Key and Cloudinary Secret Key. Copy all three and paste them in the .env file as per the naming convention in server/index.js
- MongoDB API Key: Create your MongoDB database and copy your MongoDB url and paste it int .env file and connect your application to Mongo DB.

### Installation
Download the zip or Clone the repository.
Go to client folder and run `npm install` command to install all the client side dependencies and run  `npm run dev ` to start your application.
Similarly go to the server folder and run `npm install` command to install all the dependencies and then run `npm run start` and this command will run your server
