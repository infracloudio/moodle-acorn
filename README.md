# Acorn for Moodle
======

Moodle™ LMS is an open source online Learning Management System widely used at universities, schools, and corporations. It is modular and highly adaptable to any type of online learning.

## Configure the Moodle

Moodle uses mariadb as the database and it is been used as the [services](https://docs.acorn.io/reference/acornfile#services-consuming) . If you are using Advanace Options on Acorn Platform you can provide the `moodledbname`. By default it will be named as `moodledb`.
By default username and password for moodle is `username: user` `password: bitnami`. You can changes it using `moodle_username` and `moodle_password` field.
