# Real-Time Chat Website with MERN Stack, Socket.io, Redux Toolkit, and Tailwind CSS

This is a real-time chat website that allows users to connect with others and communicate via chat in real-time. It was built using the MERN stack (MongoDB, Express.js, React.js, and Node.js), Socket.io, Redux Toolkit, and Tailwind CSS. 

## Technologies Used

- MERN stack (MongoDB, Express.js, React.js, and Node.js)
- Socket.io
- Redux Toolkit
- Tailwind CSS

## Features

- Real-time chat app where users can send and receive messages in real-time
- User authentication: users can sign up, log in, and log out using JWT
- users can create chat group and join others in the group
- Notifications: users can receive notifications on new messages
- Emojis: users can send and receive emojis in messages
- users can search and chat with them.

## Configuration and Setup
In order to run this project locally, simply clone the repository or download as zip and unzip on your local.

- Open the project in your prefered code editor.
- Go to terminal -> New terminal 
- Split your terminal into two halfs

### setup Clients

```
REACT_APP_GOOGLE_CLIENT_ID = 
REACT_APP_SERVER_URL =
```

```
$ cd clients
$ npm install 
$ npm start 
```

### setup server
```
PORT=8000
URL=
SECRET=
CLIENT_ID=
BASE_URL=
```
```
$ cd server
$ npm install 
& npm start 
```