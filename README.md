# Meanstack_chatting-App
# CHAT
This is a chat application that can be used for local usage in a small network. It creates a local server and people connected to the network can do a group or private chat. The chat also gives facilites to block someone from pinging unnecessarily.

# Instructions to run
Clone the project

git clone        
```

### DataBase - Mongo
* Check if mongodb service is running in your machine else start the service.

### Server
* You need to have node and npm installed in your machine.
* open up your teminal or command prompt go to the directory `chat`
* Do install all dependencies using  
   `npm install`  
   `npm install -g nodemon`  
   `npm start`  
Your server will be setup and ready for use.

### UI
* Go to browser and type `localhost:8080` in place of url.
* Register user by giving basic details.
* Login from the same screen.  
`Note: Handle should be unique for every user.`

# Why I started this
I had seen a lot of times during local camps that people find it difficult to interact with each other may be due to hesitation. Most of the local chats that we find will be again public and the interactions become public. So I was thinking of creating an application where people can talk in public as well as private.

# Few Screen Shots
#### Login Screen
![login screen]( "Login Page")  
#### Confirming request 
![Confirming request to chat]( "Confirming Request")  
#### Online users
![online users]( "Online users")  

#### Chatting with Friend
![Chatting]( "Chatting with Friend"


# Credits
I have used some code from AdminLTE for the chat UI. The HTML and dependent CSS.  
The private chat box has been taken from [Gurdeep Osahan](http://bootsnipp.com/Gurdeep%20Osahan).
