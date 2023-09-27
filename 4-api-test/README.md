provide:
- https://fakestoreapi.com/docs

task: 
- setup server
- create own login endpoint: "localhost:3000/auth" 
- - expected parameters: u, p; 
- - expected response: { name: string }  // combined first- and lastname
- using API to auth a user (https://fakestoreapi.com/docs#auth) and return the user
