
## Prepare the Data Path
```text
sudo mkdir /var/lib/elastiflow_es
sudo chown -R 1000:1000 /var/lib/elastiflow_es
```

## Customize Environment Variables in docker-compose.yml

## Start the  Stack using docker-compose
 where you placed the `docker-compose.yml` file run:

```text
sudo docker-compose up -d
```

## Import Dashboards of ARED analytics from routers into Kibana

The Index Patterns, vizualizations and dashboards can be loaded into Kibana by importing the required json` file from within the Kibana UI. This is done from the `Management -> Saved Objects` page.

You may also want to configure the recommend advanced Kibana settings discussed in `INSTALL.md`.
