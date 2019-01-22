# Microposts

> Example of a fullstack app using Vue.js, Express and MongoDB. You will need to edit the MongoDB connection string in server/routes/api/posts.js to your own.

## Quick Start

```bash
# Install dependencies
npm install

# Start Express Server: http://localhost:5000
npm start

# Start Vue DevServer: http://localhost:8080
cd client
npm run serve

# Build for production (Will build into server/public, ready for deployment)
cd client
npm run build
```

## App Info

### Author

Brad Traversy
[Traversy Media](http://www.traversymedia.com)

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