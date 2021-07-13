# mp-ecommerce

The idea behind the logic underlies the MVC model. With few changes but corresponding the same general structure.
About the possible changes that can be made, application-level Middleware (Express) and routing is one of them. 
In order to save time in development, in my opinion, and for the lack of scalability, routing and its requests were developed all toghether in the app.js file.
Better practice could be to bind the routing to an instance of express.Router() and work from routes folder.


```
npm start
```
