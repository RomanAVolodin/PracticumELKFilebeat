# PracticumELKFilebeat

### Запуск

```bash
docker compose up -d
```

### Маленький Flask сервер будет работать по адресу http://localhost:8080/

### Kibana будет доступна по адресу http://localhost:5601/

### Все летит в логи nginx через fileBeat в индекс  `nginx-....` а приложение в `app-...`