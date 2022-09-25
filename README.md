# Next JS Ecommerce project

Build ECommerce Website by Next.js

# Project Demo: https://next-shopping-task.vercel.app/

## Run it Locally

- git clone https://github.com/hafsamubarak/NextJS-Ecommerce-Task.git
- npm install
- npm run dev
- Open http://localhost:3000

# Project Description:

- It's a simple Ecommerce Website. The user can Register and Login into the website .
- also the user can view all products ,select a single product and make a rating and a review.
- the app allows the user to purchase the product and pay via Paypal.
- The app also has a search bar to search for products and menu of categories.
- The app has an admin dashboard to view users, orders and the admin can delete, update and create users and products.

# Technologies usef in the app:

- Next JS.
- Matreial UI.
- React JS and Context API.
- MongoDB.
- Paypal developer API.
- Vercel to deploy the app.

# Future Work:

- - to run MongoDB with local Docker container:

* step1: install Docker on your local machine.
* step2: Set up a MongoDB Docker container: Pull down the pre-built mongo image from the Docker repository: docker pull mongo
* step3: start Docker container:
  docker run
  -d
  --name YOUR_CONTAINER_NAME_HERE
  -p YOUR_LOCALHOST_PORT_HERE:27017
  -e MONGO_INITDB_ROOT_USERNAME=YOUR_USERNAME_HERE
  -e MONGO_INITDB_ROOT_PASSWORD=YOUR_PASSWORD_HERE
  mongo
* step4: Check that the container’s up and running:
  docker container ls (you should see your container listed).
* step5: Connect to the container and access your MongoDB instance: docker exec -it YOUR_CONTAINER_NAME_HERE bash
* step6: Access the MongoDB instance via the mongo command line interface:
  mongo --username YOUR_USERNAME_HERE --password YOUR_PASSWORD_HERE
  -step 7: Connecting to the database from outside of the container: (mongodb://YOUR_USERNAME_HERE:YOUR_PASSWORD_HERE@0.0.0.0:YOUR_LOCALHOST_PORT_HERE/)
