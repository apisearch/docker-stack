# docker-stack

Run apisearch stack - frontend, backend, database.

### Production

```
docker-compose up -d
```

### Development

```
docker-compose -f docker-compose.dev.yml up -d
```

- Sample data: `http://localhost:8081/heureka_cz.xml`
- Kibana: `http://localhost:5601`
- Cerebro: `http://localhost:9000`

