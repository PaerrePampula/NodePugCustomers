# NodePugCustomers
 An example application demonstrating a nodejs server with a pug engine
 It simply allows the client to save info about imaginary customers (firstname, lastname, phone and email). The saving is done on 
 the node client itself, so the info will only be saved during the runtime of the program.
 The "database" infact is simply a javascript array of some preset info and added info
#How does it work?
This runs on node js so the first requirement is to install npm and node js
Secondly, you will need the express library to run a web framework on the nodejs service
Then you will also need to install pug and body-parser as well
Pug is the templating engine, and body-parser is used to read params from forms of the user.
Once the requirements are met, run "npm run start", or "npm run dev" if you have nodemon installed.
