# Progressive Web Applications (PWA): text-editor

## Project Description

In this project, we have built a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.



To build this text editor, we had an existing application and implement methods for getting and storing data to an IndexedDB database. We have used a package called idb, which is a lightweight wrapper around the IndexedDB API. Our text ediutor app features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

## User Story

- AS A social media startup
- I WANT an API for my social network that uses a NoSQL database
- SO THAT my website can handle large amounts of unstructured data

## Acceptance Criteria

- GIVEN a social network API
- WHEN I enter the command to invoke the application
- THEN my server is started and the Mongoose models are synced to the MongoDB database
- WHEN I open API GET routes in Insomnia for users and thoughts
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete users and thoughts in my database
- WHEN I test API POST and DELETE routes in Insomnia
- THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Video Walkthrough

Since this application was build in Insomnia and we are not deploying an application, we have created a video walkthough that covers the homework assignment. 
Click here for a link to the video walk through - https://drive.google.com/file/d/1e92L4GJHdgYMimWYzU0vCiE1xm6P6oBy/view

![Alt Text](assets/socialapi.gif)

### Technologies used
- Mongoose
- MongoDB
- Express.js (for routing)
- Moment (date and time registry)

### Author

This project was written and submitted by:

Oscar Bryant https://github.com/oscarcbryant

April 10th, 2022
