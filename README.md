# Django Scaffolding

This project sets up a Django project scaffold, running on Docker, so that one
can get up and running on Django without the tedious and repetitive
bootstrapping work.


```shell
cd django-scaffolding
docker-compose up
```

Now start your browser and connect to `http://localhost`. You should see the
Django default page.

## Details

### Architecture
The setup is made of 2 components, the `api` and the `db`. The `api` of course
runs on Django, and the `db` runs Postgres.

### Django project
The Django project is simply called `project`. Other than some standard
configuration, it runs the following Django apps:
- `django_extensions`
- `rest_framework`
