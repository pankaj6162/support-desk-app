# Build & Deploy Support Desk By Socket.IO & React.JS

## Features:

- beautiful UI by react bootstrap
- display chat button on public website to start chat
- browse website while chatting with admin
- pause/resume chat with admin
- display admin dashoard
- show all users with their status (online, offline, new message)
- enable live chat with selected user
- flag new messages from online users
- support multiple users from one single page by admin

## Run

```sh
# clone project in a folder
$ git clone git@github.com:basir/support-desk-react-socket-io-final.git
# open folder in vs code
$ cd support-desk-react-socket-io-final
$ code .
# run backend
$ cd backend
$ npm install
$ npm start
# run frontend in a new terminal
$ cd frontend
$ npm install
$ npm start
```

### Chat with admin

- open http://localhost:3000
- click on Chat with us
- send message to admin

### Admin dashboard

- open http://localhost:3000/admin
- select user in left panel
- send message to user

## Lessons

1. create-react-app
   - creating support-desk-app in desktop
   - npx create-react-app frontend
   - creating layout using react-bootstrap bootstrap
2. add routing
   - create home page
   - create admin page
3. create chatbox component
   - add chat with us button
   - handle click on button
   - show support box
   - create footer section for support box
4. create web server
   - create backend folder
   - npm install socket.io express
   - create express app
   - server html files in build folder
5. create socket server
   - handle connection to the server
   - define users array
   - handle onLogin
   - handle disconnect
   - handle onMessage
   - handle onUserSelected
6. Finish chatbox
   - handle login user
   - handle list messages
   - handle send message
7. create admin dashboard
   - handle login user
   - handle list messages
   - handle send message





