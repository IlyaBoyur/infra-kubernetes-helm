# Конвертер изображений: Helm Chart

Сервис конвертации изображений: позволяет изменить размеры и расширение


## Установить Helm Chart с секретами
```bash
helm secrets install converter-release ./converter/ -f ./converter/secrets.yml
```


## Удалить Helm Chart
```bash
helm uninstall converter-release converter/
```
