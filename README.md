🔧 PHP CRUD API Generator Tool

This is a lightweight PHP-based tool that automatically generates CRUD APIs (Create, Read, Update, Delete) from a given SQL CREATE TABLE statement and a security key.

🚀 Features:

Accepts an API key for secure access.

Parses SQL CREATE TABLE syntax to generate:

✅ create_<table>.php – Insert data

✅ fetch_<table>.php – Get all records

✅ update_<table>.php – Update record by ID

✅ delete_<table>.php – Delete record by ID


Uses MySQLi prepared statements for security.

Returns JSON responses with proper errorCode and messages.

https://debbrotokumark.github.io/Api-maker/
