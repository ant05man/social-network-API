# social-network-API

## Description
This is an application where users can share their thoughts, reacts to friends' thoughts, and create a friend list. Express.js will be used for routing, and MongoDB database, and the Mongoose ODM.

## Table of Contents
-  [User Story](#userstory)
-  [Demo](#demo)
-  [Technologies](#technologies)

## User Story
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data

## Acceptance Criteria
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Demo
![Screenshot (44)](https://github.com/ant05man/social-network-API/assets/132954354/7a03c7e8-8471-4fd3-a8e4-44ad8c7d3940)
![Screenshot (45)](https://github.com/ant05man/social-network-API/assets/132954354/eb45dda4-a62c-4727-ac48-2220f474ece5)
![Screenshot (47)](https://github.com/ant05man/social-network-API/assets/132954354/0336bb1f-fe61-4def-9886-037b141a929a)

## Technologies
-  JavaScript
-  Express.js
-  Node.js
-  MongoDB
-  Mongoose
-  Insomnia
-  Moment.js

## Installation
-  Download repository to use this application on local machine
-  Node.js and MongoDB is required to use the application
-  To install necessary dependencies, command: npm install i

## License
MIT License

Copyright (c) 2023 ant05man

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
