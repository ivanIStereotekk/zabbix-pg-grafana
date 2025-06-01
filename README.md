Zabbix/Grafana/Postgres - docker compose image for quick start

- **Postgresql:**                16-alpine
- **Zabbix Server:**             7.2.1
- **Zabbix Frontend NGINX:**     7.2.1
- **Zabbix Agent:**              7.2.1
- **Grafana:**                   11.4.0


### Run docker-compose:
```
docker-compose up -d
```

The first launch takes 1-2 minutes

### Zabbix `localhost:8080`
default user password 
- **login:** Admin
- **password:** zabbix

---

### Grafana `localhost:3000` 

default user password (change `grafana/grafana.ini` auth.anonymous enabled)
- **login:** admin
- **password:** 12345

--- 

### Debug
```
docker-compose logs --tail=1 -f
```



