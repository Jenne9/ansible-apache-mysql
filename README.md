# DEPLOY APACHE AND MYSQL ON A SERVER WITH ANSIBLE

Recette-apache recipe installs Apache web server and
recette-mysql recipe installed :

- mysql-server
- create a new database
- create a new user with a pwd
- insert data into a table

Into ansible/playbooks/roles/mysql/tasks/main.yml, don't forget to replace every **** by your own datas.