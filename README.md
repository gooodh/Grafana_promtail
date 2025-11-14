## Для настройки Grafana + promtail + Node Exporter

### Скопируй репозиторий:
```bash
git clone git@github.com:gooodh/Grafana_promtail.git
```
### Запуск командой:
```bash
docker compose up -d
```
### Добавить права для папки prometheus-data:
```bash
sudo chown -R 65534:65534 ./prometheus-data
```
### Выбрать источник prometheus

### Добавить Dashboards:

- Node Exporter Full 1860
