# docker-stack

Run apisearch stack - frontend, backend, database (uses [custom Elasticsearch image](https://github.com/apisearch/elasticsearch)).

### Production

```
docker-compose -f docker-compose.prod.yml up -d elasticsearch
sleep 30
docker-compose -f docker-compose.prod.yml run --rm create-index
docker-compose -f docker-compose.prod.yml up -d apisearch web-admin
```

### Development

```
docker-compose up -d
```

- Sample data: `http://localhost:8081/heureka_cz.xml`
- Kibana: `http://localhost:5601`
- Cerebro: `http://localhost:9000`
