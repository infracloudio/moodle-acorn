# Acorn for Moodle
======

Moodle™ LMS is an open source online Learning Management System widely used at universities, schools, and corporations. It is modular and highly adaptable to any type of online learning.

## Configure the Moodle

Moodle uses mariadb as the database and it is been used as the [services](https://docs.acorn.io/reference/acornfile#services-consuming) . If you are using Advanace Options on Acorn Platform you can provide the `moodledbname`. By default it will be named as `moodledb`.
There are some field which have default values set by can be easily configured.

By default username and password for moodle is `username: user` `password: bitnami`. You can changes it using `moodle_username` and `moodle_password` field. Site Name, Email and Lang can also be changed using  `moodle_site_name`, `moodle_email` and `moodle_lang` field respectively.

##### Databases
Currently moodle supports two databases.
1. Mariadb
2. Postgress

By default it will use `mariadb` as the database. If you want to use postgres. You can use `database_type` field and provide `pgsql` as the value.

You can read more about it [here](https://github.com/bitnami/containers/tree/main/bitnami/moodle#configuration).
