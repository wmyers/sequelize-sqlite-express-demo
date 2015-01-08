A simple demo of Sequelize with SQLite in an Express app.

Basically following this [demo](http://sequelizejs.com/articles/express). Also taking missing code like `routes/users.js` from [the github repo here](https://github.com/sequelize/express-example).

This is a very quick, basic recreation of the Express demo on the Sequelize site - mainly to just show configuration for SQLite. NB you must config the `storage` property in the config for SQLite. Also note that the persistent storage db file will be auto-created *provided the containing folder exists*. So you as long as you create an empty `sqlite-db` folder then Sequelize will create the db file when it starts up, according to the config `storage` value.

I also read this these blog posts while building the demo:
[http://truongtx.me/2014/02/25/nodejs-working-with-postgresql-mysql-mariadb-sqlite-database-with-sequelize/](http://truongtx.me/2014/02/25/nodejs-working-with-postgresql-mysql-mariadb-sqlite-database-with-sequelize/)

[http://www.redotheweb.com/2013/02/20/sequelize-the-javascript-orm-in-practice.html](http://www.redotheweb.com/2013/02/20/sequelize-the-javascript-orm-in-practice.html)

Read the Sequelize docs [here](http://sequelize.readthedocs.org/en/latest/).
