# Instruction
## First step: Installing the dependencies
npm install
## Second step: Initializing the Database
mongo issuetracker scripts/init.mongo.js
## Third step: Try the mongoDB CRUD
node scripts/trymongo.js
## Forth step: Reinitialize the Database
mongo issuetracker scripts/init.mongo.js
## FIfth step: Compile the jsx file
npx babel src --out-dir public
## Sixth step: Run the server
npm start
## Final step: Check on browser
Open localhost:3000
