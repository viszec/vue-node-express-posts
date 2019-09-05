> Example of a fullstack app using Vue.js, Express and MongoDB. You will need to edit the MongoDB connection string in server/routes/api/posts.js to your own.

## Demostration
Link -> https://damp-badlands-22739.herokuapp.com/

## • Initial Backend API, Express and mongoDB
```bash
# Install node_modules
npm init

# Install expross, cors, body-parser, mongoDB
npm i express cors body-parser mongodb

# Install nodemon for server
npm i -D nodemon

###(optional)
npm install jshint(optional)
```

## • Initial Frontend with Vuejs
```bash
# Install vue/cli
npm i -g @vue/cli

# Create client
vue create client
cd client
npm run serve

# Install axios
npm i axios
npm run serve
```

## • Quick Start

```bash
# Install dependencies - Project setup
npm install

# Start Express Server: http://localhost:5000
npm start
or
npm run dev

# Start Vue DevServer: http://localhost:8080
cd client
npm run serve

# Build for production (Will build into server/public, ready for deployment)
cd client
npm run build
```

## App Info
> Special thanks to Brad Traversy for the course, if you want more references, please follow his YouTube channel.

### Author

Brad Traversy
[Traversy Media](http://www.traversymedia.com)

[Youtube](https://www.youtube.com/watch?v=j55fHUJqtyw)

### Version

1.0.0

### License

This project is licensed under the MIT License


#the css used in the video
div.container {
  max-width: 800px;
  margin: 0 auto;
  }

p.error {
  border: 1px solid #ff5b5f;
  background-color: #ffc5c1;
  padding: 10px;
  margin-bottom: 15px;
}

div.post {
  position: relative;
  border: 1px solid #5bd658;
  background-color: 3bcffb8;
  padding: 10px 10px 30px 10px;
  margin-bottom: 15px;
}

div.created-at {
  position: absolute;
  top: 0;
  left: 0;
  padding: 5px 15px 5px 15px;
  background-color: darkgreen;
}

p.text {
  font-size: 22px;
  font-weight: 700;
  margin-bottom: 0;
}


# client

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

