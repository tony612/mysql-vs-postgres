## MySQL and PostgreSQL equivalents

|Item|MySQL|PostgreSQL|
|----|-----|----------|
|command line client|mysql -u[user] -p[password] [database]|psql -U[user] -P[password] [database]|
|list databses|SHOW DATABASES;|\l|
|connect to a database|USE [database];|\c [database]|
|list tables|SHOW TABLES;|\dt|
|describe table|DESCRIBE [table];|\d [table]|
|show process list|SHOW (FULL) PROCESSLIST;|SELECT * FROM pg_stat_activity;|
|list users|SELECT * FROM MYSQL.USER;|\du|
