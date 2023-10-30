# Web Chat

1. [About](#About)
2. [Dependencies](#Dependencies)
3. [Instructions](#Instructions)

## About

# Welcome to our chat app! 

We created a web app for chatting Using nodeJS, JavaScript, React, HTML and CSS.\
The project has a Registration screen, a Login screen and a Chat screen.

**The project uses react-router and react-bootstrap packages.**

You can find the modules installed in package.json -> dependencies. When running ```npm install``` installations are made according to this file.

You can login by entering a name and password (Username: Mor Siman Tov, password: 1234567u):

![image](https://github.com/morsimantov/Chat-App-Web/assets/92635551/ee853da3-64d7-4c87-a4d1-fb0eb421c32f)

Than you'll be represented by the chats screen:

![image](https://github.com/morsimantov/Chat-App-Web/assets/92635551/841e7c3a-e226-4858-bb8d-2de0b51a4025)

If you click the clip icon on the bottom left of the chat window, 3 different options will appear. You can send all sorts of media, like a photo.

You can also send an audio recording:

![image](https://github.com/morsimantov/Chat-App-Web/assets/92635551/2a8b3e70-31b9-4879-9d25-5ed311546570)

Or upload a video:

![image](https://github.com/morsimantov/Chat-App-Web/assets/92635551/2540b43c-ea55-4c25-bb9c-a7c15f626c97)



## Dependencies

* Download Node.js : https://nodejs.org/en/ which includes NPM (a package manager for NODE. Js) and will be installed on your computer when you install Node.js. 
* Clone the repository
* Install dependencies using:
  ```npm install```
* Run using:
  ```npm start```  
* The project uses react-router and react-bootstrap packages.
* Modules installed can be found in package.json -> dependencies


## Instructions

* In order to log in with the user we created please enter the following:\
**Username: Mor Siman Tov**\
**Password: 1234567u**
* Running the program leads to the Login screen (run by opening the terminal and then ```npm start```)
* If not already registered, by pressing the "Click here" button you will be navigated to the Registration screen.
* By entering a correct registered (and for now hard coded) username and password, you will be able to log in.\
  Onced logged in you will be navigated to the Chat screen.
* When in the chat screen, the contacts of current user are shown on the left,\
  and by clicking on any one of them, chat message history is shown.
* **The user we created (by the username "Mor Siman Tov") has 6 contacts, 5 are shown when entering the Chat screen and have exisiting chats containing messages of type text, image, video and audio. There is another contact with the username "Emma Watson", that can be added by clicking the "add" button on the top right of the chat screen.**  
* Sending a new message:
  * Sending a new text message is done by typing and clicking the send button or by pressing Enter
  * Sending a new voice message is done by clicking the link logo and then -\
    pressing one time on the microphone icon - to start the recording, and by pressing again on the same button - the recording is stopped and sent.
  * Sending a new photo/video is done by clicking the photo/video icon and choosing a photo/video to send.
* Adding a new contact is done by pressing the logo with the plus sign, and entering an existing (hard coded) contact. If an existing contact name was entered, the chat will appear with its message history.
