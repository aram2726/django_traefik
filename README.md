# Docker django traefik

* To run app

```
$ cd infrastructure
$ docker-compose up -d --build
$ docker-compose exec web python manage.py migrate --noinput
```

Now you can visit http://django.localhost:8008/ and see django starter template.
And http://django.localhost:8081/dashboard/#/ to see traefik dashboard.


* To shut down

```
$ docker-compose down -v
```

-----------------------------------------------------------------------------------------

Thanks testdriven.io for this article https://testdriven.io/blog/django-docker-traefik/
