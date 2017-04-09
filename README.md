# whisky_app

run webpack from client folder - webpack -w.

run server with nodemon server.js

run mongod with mongod

seed database with mongo < seeds.js

can check db with mongo and then view:

DATABASE NAME : whisky

Collection name: whisky_distilleries


API can be viewed on isomnia @ localhost:3000/api/locations ensure steps above have been followed and webpack,nodmon,mongod are running and db has been populated with seeds.



# Users are now available via API: 

ensure all services are running as above and database has been seeded with mongo < seeds.js

users API can be accessed using isomia @ localhost:3000/api/users

this will present all users, grab one of there id's will look something like 58ea5f29c64230cb3bbf2c31

you can then perform a get request for that user by using localhost:3000/api/users/58ea5f29c64230cb3bbf2c31

also a PUT request can be performed by using the same format above and providing values.

note: if you reseed database id's will change.
