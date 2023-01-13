创建index 先。
```bash
docker compose exec quickwit quickwit index create --index-config /quickwit/index-config.yml
```

删除index
```bash
docker compose exec quickwit  quickwit index delete --index applog
```