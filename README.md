A simple boilerplate project to implement AWS S3 file upload functionality in a Node, React and Mongo app. Using Multer for uploading file.

To launch this project in the local machine

First start mongodb service with `sudo service mongod start` and then the following commands

- Run `npm install`
- Run `npm run dev`
- Run `npm start`

It will start the server at [http://localhost:3000/](http://localhost:3000/)

### Most importantly remember to replace AWS S3's bucket_name, AWSAccessKeyId and AWSSecretKey wth your own. I have kept those keys of mine in the .env file in the project root, and which ofcourse have been put in the gitignore file so not be make them public.

<img src="AWS_S3-1.png">

<img src="app-running-in-localhost.png">

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

[NOTE ONLY FOR ME - I HAVE TO ENTER ALL DETAILS IN .env FILE AGAIN AS I HAVE DELETED THE S3-BUCKET ]