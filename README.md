# NodeJS-Express-Mongo

## Run MongoDB Community Edition

Follow these steps to run MongoDB Community Edition. These instructions assume that you are using the default settings.

You can run MongoDB as a macOS service using brew, or you can run MongoDB manually as a background process. It is recommended to run MongoDB as a macOS service, as doing so sets the correct system ulimit values automatically (see ulimit settings for more information).

- To run MongoDB (i.e. the mongod process) as a macOS service, issue the following:

> brew services start mongodb-community@4.4

- To stop a mongod running as a macOS service, use the following command as needed:

> brew services stop mongodb-community@4.4

- To run MongoDB (i.e. the mongod process) manually as a background process, issue the following:

> mongod --config /usr/local/etc/mongod.conf --fork
