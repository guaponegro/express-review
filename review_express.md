What is middleware, and whats a useful example?

Middleware is software that is between your OS and your applications. A---- The middleware allows for communication between your apps for smoother functionality. A great example of this is method-override. Method-override allows you to have a delete route by overriding the GET or PUT method.

What are the HTTP verbs and what's the difference between them?
A---- HTTP stands for HyperText Transfer Protocol and is used in URLs to transfer and format messages in web servers and browsers. The verbs that HTTP uses are GET, PUT, POST, and DELETE. GET retrieves data from your server. PUT creates a new resource or replaces resource. POST sends data to the server. DELETE removes the resource that you have specified.

Describe the two patterns of asynchronous functions- callbacks vs async await.
A---- Callbacks- a piece of code that is passed through other code and is expected to execute a request.
Async and await- allows you to execute other code, while waiting for another task to happen later

What is a model and what does it help us do?
A---- A model is a design structure that allows you to manipulate and change objects on a page

What is session?
A---- Session- an interactive information exchange between 2 or more devices or a computer and user for a set period of time

I'm getting an error from my template- cannot read 'name' of undefined. What should I check and where?
A---- You want to check your model and see if you have property "name" being defined. If so, check to see if you have required that model in the necessary areas, specifically the controller file.

I'm getting an error- "cannot cast to ObjectId for value 'new' at value '_id' for model Review". What the heck does that even mean???
A---- Mongoose is trying to get the ObjectId for model Review but cannot properly query the ObjectId at value _id. 

Describe the necessary parts of a form to properly submit to our server. What are some common things to forget or do improperly that will result in bad responses/data?
A---- To submit a form to a server, you have to have your text in between html tags. You then need to have a path for the HTTP methods to interact with the page and have a value for the form. If you have any issues, you need to log req.body because that is where your information is held.

Tell your 5 year old cousin how the internet works.
A---- Every website has something called a URL, which is like an address. When you want to go to a site (ex. Google) and click send, you breakdown the information into tiny data pieces and it gets sent through the Wi-Fi to your router. Your router sends that data to a server, which holds a bunch of other data. The server finds the address of the site you want to go to, pulls that information and then links it back to your router, which puts you at the home page of the site.

ALGORITHM CHALLENGE: 

In a seperate javascript file, write a LinkedList that works as a priority queue- when you add a new node to the list, it is given a number and finds its spot in line based on that number. Your linkedlist should have the following methods:

add(data, priority)
search(data)
remove() -> remove the head node from the list.