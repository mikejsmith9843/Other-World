# Other-World
week-18 Challenge (MongoDB)

## Table of Contents
 * Description
 * Live Screen Recording
 * Screenshots
 * Tech Used
 * Installation
 * Credits
 * Usage Info
 * Suggested-Future-Develpment
 * Contribution-Guidelines
 * Test-Instructions
 * License
 * Questions

## Description
This application was created as the start of a full stack social network application using a MongoDB database, Express.js routing, and the Mongoose ODM. It sets up the initial CRUD API routes for said application which allow users to be created, searched for, updated, and deleted. Users can also share their thoughts, react to friends' thoughts, create a friend list, and subsequently delete thoughts, reactions, friends, and themselves as a user. Although this application is still at the ground floor of its full potential, the MongoDB database and API middleware routing is an integral first step in leaning about the potential of MongoDB and the Mongoose ODM.

Some of the main challenges I encountered when creating this application were that although MongoDB is much more fluid and loose than Sequel (SQL) when it comes to how data is queried and added to the database, I did notice that the errors were much more elusive creating troubleshooting much more difficult. Also finding the most efficient ways to delete data on cascade and join tables was a challenge. Since MongoDB seems to require less code than SQL, there was a bit of a learning curve since there is a lot happening under the hood that I still have yet to fully understand.

With the exception of the challenges faced, I did learn yet another powerful tool within the MERN stack to add to my knowledge of full stack development. With this application I hope to continue its development adding a full-front end UI with React, in turn creating a full stack application strictly through the use of MERN.

## Live Screen Recording


## Screenshots


## Tech Used
This application is powered by Node.js (v16.19.1), Express.js (v.14.18.2), JavaScript, MongoDB, and Mongoose (ODM). It utilizes the node package manager (npm) dependencies express (v4.18.2), and mongoose (v7.2.2). Nodemon (v2.0.22) was utilized as a devDependency allowing the server to refresh when edits were made to application. Jest (v.29.5.0) is installed as a devDependency for future unit testing. MongoDB Compass acted as the interactive shell used to visually see the database. Also, the Insomnia application, was utilized to test the functionality of routes within the program.

NodeJS Express.js MongoDB JavaScript NPM Nodemon Jest Insomnia

## Installation
1. Clone the repo
2. Open in Vs Code. If you do not have VS Code you must install it.
3. Using the terminal, install node.js.
4. Once node.js is installed, in the terminal, utilize the command npm init -y to initalize and create a package.json where project files will be stored.
5. Next, use the terminal ro run the command npm i to install the dependencies associated with this application
  * Command for express will be npm i express
  * Command for mongoose will be npm i mongoose
  * command for nodemon willl be npm i nodemon
  * command for jest will ne npm i jest
6. Next, you will want to make sure you have access to a MongoDB account and MongoDB Compass, these will allow you to interact with the database and visually confirm what changes are being made in the database.
7. Once all dependencies are installed, you will then be able to run the command npm start from the root directory to spin up the server. With nodemon installed, you will also be able to utilize the command npm run dev to keep the server spun up between code edits.
8. From there, you can utilize applications such as Insomnia to test the functionality of the API routes within the program and make edits to the code base.

## Credits
N/a

## Features
Features of this application include the ability to create users/thoughts, find all users/thoughts, find a single user/single thought, update user/thought information, and delete a user/thought. The ability to add reactions to particular thoughts, and friends to users is also a notable feature -> when a thought, reaction, or friend is added to the database, it will update within the user object accordingly.

## Usage Information
As of now the usage of this application can be conducted through spinning up the server with npm run start or nodemon with npm run dev, then heading over to an application like Insomnia or Postman and testing different API end points. For further information on starting up the server, MongoDB Compass and MongoDB installation navigate to the Installation section above.

## Suggested Future Development
N/A

## Contribution GuideLines
N/A

## Test Instructions
There is currently no unit testing written yet for this application.

## License
N/A

## Questions 
Have additional questions? Click the links below to reach me through my GitHub account or Email address.

[Link to github](https://github.com/mikejsmith9843)

[Email](Mikejsmith9843@gmail.com)