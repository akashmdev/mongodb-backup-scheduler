## About

Scheduled [mongodb](https://www.mongodb.com/) backup using nodejs.

## Getting Started

Getting up and running is as easy as 1, 2, 3.

1. Make sure you have [NodeJS](https://nodejs.org/) and [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/cli/install) installed.
2. Install your dependencies

    ```
    cd path/to/mongodb-backup-scheduler
    yarn or npm install
    ```

3. Start your app

    ```
    yarn dev
    ```
   
##Other Info
Basic mongo dump and restore commands, they contain more options you can have a look at man page for both of them.
1. mongodump --db=rbac_tutorial --archive=./rbac.gzip --gzip
2. mongorestore --db=rbac_tutorial --archive=./rbac.gzip --gzip

Using mongodump - without any args:
will dump each and every db into a folder called "dump" in the directory from where it was executed.

Using mongorestore - without any args:
will try to restore every database from "dump" folder in current directory, if "dump" folder does not exist then it will simply fail.
