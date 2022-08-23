#FETCH PRODUCTS FROM BACKEND

Step One:Create the app
1.created a folder called FetchProducts
2.npx create-react-app frontend
3.npm start

Step Two:List the products
1.create a file in src folder called data
2.list the items in the file
3.style in index.css

Step Three: Create backend server
1.Create backend folder in the root folder
2.run npm init in the backend folder
3.update package.json "type=module" to use ES6 module import instead of require
4.create server.js
5.npm install express then run backend i.e node serve.js
6.install nodemon in backend  
 npm install nodemon --save-dev
7.update package.json to use nodemon
8.run bakcend using npm start

Step Four: Fetch the data from backend
1.copy the list details to another file in backend i.e data.js
2.set proxy in frontend folder package.json
3.npm install axios in frontend
4.use state,  use effect,  use reducer hooks
