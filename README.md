# TIPS AND TRICKS

## Practicing
* **https://www.w3schools.com/sql/trysql.asp?filename=trysql_asc** - practice sql website. Use any browser other than Firefox

## Switches
* **-h** - host
* **-u** - user
* **-p** - requires password
* **-e** - outputs to a file
  * Ex: mysql -h HOSTNAME -u USER -p DATABASE "<query>" > output.txt

## Basic Commands
* **SHOW WARNINGS** - can be used after a warning is encountered
* **FLUSH PRIVILEGES** - reimplements all privileges
* **SHOW PROCESSLIST** - shows all querys and processes currently running
* **CONCAT_WS** - puts the first string mentioned in between all other arguments
  * Ex: SELECT * CONCAT_WS('-', first_name, last_name) FROM users
