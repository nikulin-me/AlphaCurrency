# AlphaCurrency

___
**Запуск приложения**

```
docker pull nikulinme/alphaimg
docker run -p 8080:8080 --rm -d --name alphac nikulinme/alphaimg
```

___
Endpoints
```
GET /currency/{YOUR_CURRENCY}   - get delta between yesterday and today
GET /gif/{YOUR_CURRENCY}        - get gif depending of delta. if minus delta- broke else: rich
GET /gif/{YOUR_CURRENCY}/json   - get gif data in json
```