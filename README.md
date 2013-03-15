mysql-to-mongo
==============

Mysql Database to MongoDb Script PHP

Php file to convert mysql to mongodb.
You have to run this file on browser or using telnet.
You may also try php index.php . But this will sometime create error which would be
PHP Fatal error:  Class 'MongoClient'
This is caused when you don't have mongo driver installed or there might be problem with
API module of php.

In this file you have to change only these things:

define('dbname', 'YOUR_DB_NAME');
private $dbhost='DATABASE_HOST'; 
private $dbusername='DATABASE_USERNAME';
private $dbpassword='DATABASE_PASSWORD';

Dbname for both mongo and mysql should be same
Dont worry if mongodb database is not present. It will automatically create for you with all the collection details.

NOTE: This converts all the data to string from mysql to mongo.
