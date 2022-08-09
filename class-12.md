# Reading Notes
Reading
Status Codes Based On REST Methods

In your own words, describe what each group of status code represents:

100’s = informational status code
200’s = success!/ request accepted
300’s = redirection/ resource isn't here anymore
400’s = client error code / client has wrong uri, or authorization problems
500’s = server error code /overwhelmed or unreacheable server
What is a status code 202?

Accepted (used for asychronous processing), request was valid but wait for processing.

What is a status code 308?

permanent redirect/ use another url

What code would you use if an update didn’t return data to a client?

204 no content

What code would you use if a resource used to exist but no longer does?

status code 308

What is the ‘Forbidden’ status code?

403 forbidden the client has no permissions to access resource despite authorizing it.

Videos
Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

Why do we need to pull our MongoDB database string out of our server and put it into our .env?
So it's updated when deployed .

What is middleware?

code that's ran after the server gets a request but also before it reaches the client

What does app.use(express.json()) do?

let's the server accept JSON as the body.

What does the /:id mean in a route?

it's a route where the user get's an id
What is the difference between PUT and PATCH?

PUT means a full update while PATCH means partial.
How do you make a default value in a schema?

by creating a model file that has a schema and the data properties

What does a 500 error status code mean?

server error

What is the difference between a status 200 and a status 201?

200 is default success 201 is a successfully created resource.