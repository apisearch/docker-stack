# docker-stack

Run apisearch stack - frontend, backend, database.

### Production

```
docker-compose -f docker-compose.prod.yml up -d
```

### Development

```
docker-compose up -d
```

- Sample data: `http://localhost:8081/heureka_cz.xml`
- Kibana: `http://localhost:5601`
- Cerebro: `http://localhost:9000`
