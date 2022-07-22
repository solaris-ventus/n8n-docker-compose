# n8n on Subfolder with SSL

Starts n8n and deployes it on a subfolder


## Start

To start n8n in a subfolder simply start docker-compose by executing the following
command in the current folder.
```
mkdir -p /home/user/data-docker/n8n/
```

**IMPORTANT:** But before you do that change the default users and passwords in the `.env` file!

```
docker-compose up -d
```

To stop it execute:

```
docker-compose stop
```

Все что в `<...>` надо актуализировать под себя

p.s. Все так или иначе собрано на основе предоставленных примеров документации и репозитариев n8n:<br>
[Sample from github repo](https://github.com/n8n-io/n8n/tree/master/docker)<br>
[Settings PG. docs](https://docs.n8n.io/hosting/installation/docker/#postgresdb)<br>
[docker-compose sample. docs](https://docs.n8n.io/hosting/server-setups/docker-compose/)