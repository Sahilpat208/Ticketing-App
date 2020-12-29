# Ticketing-App
Functionality :
User Can list a ticket for an event for sale
Other user can purchase this ticket
Any user can list tickets for sale and purchase ticket
When any user wants to purchase a ticket, User has only 10 minutes to buy and tickets gets locked for 10 minutes.
While locked, no other user can purchase the ticket. After 10 minutes, the ticket should 'Unlock'
Ticket prices can be edited  if they are not in lock condition.

Implementation:
A Server-Side-Rendered React app using Hooks and Next.js . To limit access to your APIs using JWT-based authentication. 
Each service is using shared common libraries (NPM Modules ) and created using Node and Express plus has its persistent storage in either a Mongo database or Redis.
The entire app is deployed and runs in Docker containers executed in a Kubernetes cluster.
All of the code was written with Typescript.

