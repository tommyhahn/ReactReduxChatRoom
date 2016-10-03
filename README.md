Use Guide:

1. clone the repository and then cd react-redux-socketio-chatand npm install

2. Setting up MongoDB

  Once you've installed MongoDB start up the MongoDB server in a new terminal with the following commands:

  mkdir db
  mongod --dbpath=./db --smallfiles
  Then open a new terminal and type in mongo and type in use chat_dev This is your database interface. You can query the         database for records for example: db.users.find() or db.stats().

  Now that you've done all that, you can go go ahead and code away!

3. Development

  npm run dev
  And then point your browser to localhost:3000

  To hide the dev tool panel press ctrl+h
  To change position press ctrl+m

4. Production

  npm run build
  npm start
  And then point your browser to localhost:3000
