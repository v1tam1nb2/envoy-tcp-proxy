# envoy-tcp-proxy
EnvoyによるTCPプロキシ

client --> envoy --> clickhouse

# 構築

```
git clone https://github.com/v1tam1nb2/envoy-tcp-proxy.git
cd envoy-tcp-proxy
docker-compose up -d
```


# 確認

```
curl localhost:9000
    Port 9000 is for clickhouse-client program
    You must use port 8123 for HTTP.
```