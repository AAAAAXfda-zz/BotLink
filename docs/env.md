<!---
File generated by cli. DO NOT EDIT.
-->

# ENVIRONMENT

|Name | Default Value | Description |
|---|---|---|
| "SERVICE_NAME" | api |  |
| "SERVICE_NAME" | billing |  |
| "SERVICE_NAME" | cli |  |
| "SERVICE_NAME" | csi |  |
| "SERVICE_NAME" | link |  |
| "SERVICE_NAME" | logger |  |
| "SERVICE_NAME" | metadata |  |
| "SERVICE_NAME" | notify |  |
| "FEATURE_TOGGLE_ENABLE" | false |  |
| "FEATURE_TOGGLE_API" | http://localhost:4242/api/ |  |
| "LOG_LEVEL" | logger.INFO_LEVEL |  |
| "LOG_TIME_FORMAT" | time.RFC3339Nano |  |
| "MQ_ENABLED" | false | Enabled MQ |
| "SENTRY_DSN" |  | key for sentry |
| "TRACER_URI" | localhost:6831 | Tracing addr:host |
| "STORE_TYPE" | ram | Select: postgres, mongo, mysql, redis, dgraph, sqlite, leveldb, badger, ram |
| "STORE_BADGER_PATH" | /tmp/links.badger | Badger path to file |
| "STORE_DGRAPH_URI" | localhost:9080 | DGRAPH URI |
| "STORE_LEVELDB_PATH" | /tmp/links.db | LevelDB path to file |
| "STORE_MONGODB_URI" | mongodb://localhost:27017/shortlink | MongoDB URI |
| "STORE_MODE_WRITE" | storeOptions.MODE_SINGLE_WRITE | mode write to db |
| "STORE_MYSQL_URI" | shortlink:shortlink@(localhost:3306)/shortlink?parseTime=true | MySQL URI |
| "STORE_POSTGRES_URI" | postgres://postgres:shortlink@localhost:5432/shortlink?sslmode=disable | Postgres URI |
| "STORE_MODE_WRITE" | options.MODE_SINGLE_WRITE | mode write to db |
| "STORE_MODE_WRITE" | options.MODE_SINGLE_WRITE | mode write to db. Select: 0 (MODE_SINGLE_WRITE), 1 (MODE_BATCH_WRITE) |
| "STORE_REDIS_URI" | localhost:6379 | Redis URI |
| "STORE_SQLITE_PATH" | /tmp/links.sqlite | SQLite URI |
| "STORE_TYPE" | ram | Select: postgres |
| "MQ_TYPE" | rabbitmq | Select: kafka, rabbitmq, nats |
| "MQ_KAFKA_URI" | localhost:9092 | Kafka URI |
| "MQ_KAFKA_CONSUMER_GROUP" | shortlink | Kafka consumer group |
| "MQ_RABBIT_URI" | amqp://localhost:5672 | RabbitMQ URI |
| "MQ_RECONNECT_DELAY_SECONDS" | 3 | RabbitMQ reconnects after delay seconds |
| "API_TYPE" | http-chi | Select: http-chi, gRPC-web, graphql, cloudevents, go-kit |
| "API_PORT" | 7070 | API port |
| "API_TIMEOUT" | 60 | Request Timeout (seconds) |
| "PAYMENT_SNAPSHOT_CRON" | * * * * * | check snapshot by timeout |
| "API_TYPE" | http-chi | Select: http-chi |
| "API_PORT" | 7070 | API port |
| "API_TIMEOUT" | 60 | Request Timeout (seconds) |
| "STORE_TYPE" | postgres | Select: postgres |
| "STORE_TYPE" | postgres | Select: postgres |
| "STORE_TYPE" | postgres | Select: postgres |
| "STORE_TYPE" | ram | Select: postgres, mongo, mysql, redis, dgraph, sqlite, leveldb, badger, ram |
| "STORE_MODE_WRITE" | options.MODE_SINGLE_WRITE | mode write to db. Select: 0 (MODE_SINGLE_WRITE), 1 (MODE_BATCH_WRITE) |
| "STORE_MODE_WRITE" | options.MODE_SINGLE_WRITE | mode write to db. Select: 0 (MODE_SINGLE_WRITE), 1 (MODE_BATCH_WRITE) |
| "STORE_MODE_WRITE" | options.MODE_SINGLE_WRITE | mode write to db. Select: 0 (MODE_SINGLE_WRITE), 1 (MODE_BATCH_WRITE) |
| "STORE_TYPE" | ram | Select: postgres, mongo, mysql, redis, dgraph, sqlite, leveldb, badger, ram, scylla, cassandra |
| "BOT_SLACK_WEBHOOK" | YOUR_WEBHOOK_URL_HERE | Your webhook URL |
| "BOT_SMTP_FROM" | example@site.com |  |
| "BOT_SMTP_PASS" | YOUR_PASSWORD |  |
| "BOT_SMTP_TO" | EMAIL_USER |  |
| "BOT_SMTP_HOST" | smtp.gmail.com |  |
| "BOT_SMTP_ADDR" | smtp.gmail.com:587 |  |
| "BOT_TELEGRAM_WEBHOOK" | YOUR_WEBHOOK_URL_HERE | Your webhook URL |
| "BOT_TELEGRAM_CHAT_ID" | 123 | Your chat ID |
| "BOT_TELEGRAM_DEBUG_MODE" | false | Debug mode |
| "LOG_LEVEL" | logger.INFO_LEVEL |  |
| "LOG_TIME_FORMAT" | time.RFC3339Nano |  |
| "LOG_LEVEL" | logger.INFO_LEVEL |  |
| "LOG_TIME_FORMAT" | time.RFC3339Nano |  |
| "GRPC_CLIENT_TLS_ENABLED" | false | gRPC tls |
| "GRPC_CLIENT_PORT" | 50051 | gRPC port |
| "GRPC_CLIENT_HOST" | 0.0.0.0 | gRPC host |
| "GRPC_CLIENT_CERT_PATH" | ops/cert/intermediate_ca.pem | gRPC client cert |
| "GRPC_CLIENT_LOGGER_ENABLE" | true | Enable logging for gRPC-client |
| "GRPC_SERVER_TLS_ENABLED" | false | gRPC tls |
| "GRPC_SERVER_PORT" | 50051 | gRPC port |
| "GRPC_SERVER_HOST" | 0.0.0.0 | gRPC host |
| "GRPC_SERVER_CERT_PATH" | ops/cert/shortlink-server.pem | gRPC server cert |
| "GRPC_SERVER_KEY_PATH" | ops/cert/shortlink-server-key.pem | gRPC server key |
| "GRPC_SERVER_LOGGER_ENABLE" | true | Enable logging for gRPC-client |