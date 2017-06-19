# Ionic 3 roles server
This application is the server part of a demo that implements and shows the authentication and roles management in a Ionic 3 application.
The server uses Passport to manage the authentication, JWT tokens to maintain the session open and Express to manage the requests.

![Dependencies status](https://david-dm.org/dnchia/Ionic3-roles-server.svg)

## How to use it
With NodeJS installed, use: `node server.js`

### Configuration
The file database.js must be modified to introduce the direction of the MongoDB.

## References
This demo example was done following the tutorial made by Joshua Morony ([@joshuamorony](https://github.com/joshuamorony)) in 
[Creating Role Based Authentication with Passport in Ionic 2 - Part 1](https://www.joshmorony.com/creating-role-based-authentication-with-passport-in-ionic-2-part-1/),
all credits to him.

## In the future
The server will fully redone using TypeScript and changing its structure to fit more good design principles.
Also more functionality will be added.