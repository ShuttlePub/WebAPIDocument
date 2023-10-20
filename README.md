# WebAPI Document

# Archived

https://github.com/ShuttlePub/document に移行しました。

https://docs.shuttle.pub

## For developers

docker-composeが使えます。現状は`documents/v1.yaml`を対象に動作するように構築しています

`sudo docker-compose up -d`

- `http://localhost:8001`: SwaggerEditor
- `http://localhost:8002`: SwaggerUI
- `http://localhost:8003`: MockServer

> In fact, it is better to use IDEA with [swagger plugin](https://plugins.jetbrains.com/plugin/14837-openapi-swagger-editor).
