
# Django-docker

**django-docker** is basic configuration of Django project with PostgreSQL. Additionally i made interacting with docker easier by applying Laravel Sail like way.


## Deployment

Basically download zip file of this repository, then exctract and change name of folder to your desired project name.

Then build your containers.

```bash
docker build .
```
To run your app just use.
```bash
./django-sail up #optional arguments like -d --build etc.
```
Using **./django-sail** you can run (probably) any django related command.
```bash
./django-sail migrate
```
If you run into any issues, just let me know by creating issue no repository :)

