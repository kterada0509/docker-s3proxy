# docker-s3rver

## How to use

### Run Docker

```
docker-compose -f docker-compose.yml up --build -d
```

### Create Bucket

```
aws  s3 mb s3://hogehoge --endpoint-url "http://localhost:8080"
```

### List Bucket
```
aws  s3 ls s3:// --endpoint-url "http://localhost:8080"
```
