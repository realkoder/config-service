# Config-Server

This will return the properties configured from the config-repo default:
```bash
curl http://localhost:8888/catalog-service/default
```

This will return the properties configured from the config-repo prod profile:
```bash
curl http://localhost:8888/catalog-service/prod
```