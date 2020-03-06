# mongo-db
If there is an error in MongoDB use the following code.
Try the following methods, be sure one of them will help.
/***********************************/

mongod --storageEngine=mmapv1 --dbpath [your-path]

mongod --config c:\mongodb\bin\startmongo.conf

mongod --config C:\Program Files\MongoDB\Server\3.2\bin\startmongo.conf

mongod --storageEngine=mmapv2

mongod.exe --storageEngine=mmapv1

mongod.exe --dbpath c:\data\db --journal  --storageEngine=mmapv1

// Code runeing - Use this code when you run Mongo before and today it doesn't.

mongod.exe --storageEngine=mmapv1 --dbpath "c:\data"

mongod --dbpath C:\data\db

/*******************************************/

Normally this caused because you didn't start mongod process before you try starting mongo shell.

Start mongod server

mongod

Open another terminal window

Start mongo shell


/********************/

change port running mongo db

mongo or mongo --port 27017

mongo
