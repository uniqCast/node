### Node.js Task2

Continued onto [Task1](https://github.com/uniqCast/node/blob/master/task1/README.md) 
you should now create a microservice which holds particular information in its database.

In order to complete this task, you should do the following:
 * initialize an SQLite database using [Sequelize](http://docs.sequelizejs.com/en/latest/)
 * create and sync a database model consisting of columns  ```id (integer, primary key)```, ```content_uid (string)```, ```expires (datetime)```
 * install, setup and run a [NATS server](https://github.com/nats-io/gnatsd) locally on your computer
 * connect to NATS with [node-nats](https://github.com/nats-io/node-nats)
 * subscribe to queues called "content.add" and "content.list" and write all received data to stdout
