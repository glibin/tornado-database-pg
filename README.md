tornado.database like Postgresql wrapper
===================

Postgresql db wrapper similar to tornado.database.

Usefull then migrating from MySQL to Postgresql.

Main difference from tornado.database:

*   `execute` returns `rowcount` not `lastrowid`
*   you need to specify `RETURNING id;` in `execute_lastrowid` statements