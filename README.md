# blogList-backend
This is the backend of a fullstack application that let's you login (if you created a user) and save blogs that may interest you. 
It is a RESTful API build with Node/Express and MongoDB as the database for the documents and users saved by the App.

## TO MAKE IT WORK: 
1. Fork the repo, install all dependecies and create a new cluster in MongoDB Atlas. 
2. You will have to populate the .env file with four env variables:
###### MONGO_URI  = yourclusterURI (EXAMPLE: mongodb+srv://yourusername:RandomString@cluste0.xgnsz3c.mongodb.net/blogList?retryWrites=true&w=majority)
###### TEST_MONGO_URI = yourcluster(EXAMPLE: mongodb+srv://yourusername:RandomString@cluste0.xgnsz3c.mongodb.net/testBlogList?retryWrites=true&w=majority)
###### PORT = 3003 (the app listen that port by default)
###### SECRET = anystring (This is for JasonWebToken so you can use any string that u want.)

NOTE: The MONGO password used in the env variables are given to you when you create the cluster and click on "connect".
                                                                  
3. After setting this things, run in the console `npm start` to lift the server or `npm run dev` to start it with nodemon in development mode.

That's it! Put the frontend to work and start saving, liking or deleting your blogs!😄 
                                                              
