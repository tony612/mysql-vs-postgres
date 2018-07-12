## MySQL and PostgreSQL equivalents

|Item|MySQL|PostgreSQL|
|----|-----|----------|
|command line client|mysql -u[user] -P[port] -p -h[host] [database]|psql -U[user] p[port] -W -h[host] [database]|
|list databses|SHOW DATABASES;|\l|
|connect to a database|USE [database];|\c [database]|
|list tables|SHOW TABLES;|\dt|
|describe table|DESCRIBE [table];|\d [table]|
|show process list|SHOW (FULL) PROCESSLIST;|SELECT * FROM pg_stat_activity;|
|list users|SELECT * FROM MYSQL.USER;|\du|
