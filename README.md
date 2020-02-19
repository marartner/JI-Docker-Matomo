# Matomo/Mysql - Basic Docker Setup

Run:
```sh
docker-compose up
```

Then open up `localhost:8080` in your browser, go through initial setup. 
Accept the default database configuration and set up your superuser and first project.

Afterwards, edit `config/config.ini.php` to add the line `trusted_hosts[] = "localhost:8080"` in the `[General]` section. 
