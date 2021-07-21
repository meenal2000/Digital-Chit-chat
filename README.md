# Digital-Chit-chat

High-level explaination -
It is real-time chat application where the user can select any room and text another person . The user can also change it's username . 
It uses firebase as the backend , so all the data gets saved and retrieved from there . It also make use of browser's local storage . So, if the user comes back , he will have it's previous username and not anonymous .

Low-level explaination -
For the front-end part , I mainly used HTML and Bootstrap . I also added some of my own styles using CSS where it was necessary .  All the chats are saved and retrieved from the firebase which is acting as a back-end here . There are mainly 3 JS files -
1. App.js
2. ui.js
3. chat.js

App.js - It is something like a glue which joins everything of our project

chat.js -  adding new chat documents
setting up a new real-time listener to get new chats
updating the new user-name
updating the new room

ui.js - render chat templates to the DOM
clear the list of chats when the room changes
