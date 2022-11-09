# A MERN stack app(Todo app) with React.js + node.js + express.js + mongodb with REST API

### Front-End - React.js

### Back-End - Node.js, Express.js & MongoDB Atlas

🖐 Hi there, It's a full-stack app built in React.js for the frontend and Node.js for the backend. And I've used Mongodb's atlas as a cloud service provider to store data. This app is a simple TODO APP, this is just to showcase the basic working of a Full-stack application built in MERN. This app includes all the CRUD operations performed via exposed APIs. Please free to go through this code and enjoy! Hope you got the insights

## 📦packages used:

**Frontend -**

1.  react-bootstrap : for frontend CSS framework

**_Backend -_**

1.  express-validator - Input validation
2.  mongoose - ODM
3.  express - node.js framework

## API Endpoints

    http://localhost:8080/get
    http://localhost:8080/get/${id}
    http://localhost:8080/post
    http://localhost:8080/delete/${id}
    http://localhost:8080/put/${id}

## 📸 ScreenShots:

Initial Page
![Initial page](https://images2.imgbox.com/4c/52/0KsbiqwY_o.jpg)

Add Todo
![Add todo](https://images2.imgbox.com/af/a5/KFCyJQOt_o.jpg)

Mark Todo
![Mark Todo](https://images2.imgbox.com/24/8e/G15Igd6E_o.jpg)

## 😀How to use this project

1. Well, first clone or download this repo.
2. Create a cluster in mongodb Atlas, and then create a collection, and get your access URL to your cluster's database and paste it in **_`app.js`_** for **_`MONGODBURL`_** variable.
3. In Root folder, Run `npm install` to install dependent packages for the Node.js server.
4. In Client folder, Run `npm install` to install dependent packages for the React app.
5. Now, you're ready to go!

## 📰License

[MIT](https://choosealicense.com/licenses/mit/)
