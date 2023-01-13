# redis-dashboard
Redis dashboard project for fun.

## backend api command
### put key
```bash
curl -X PUT -H "Content-Type: application/json" http://localhost:10004/api/redis/keys -d '{"key":"k1","value":"v1"}'
```
### delete key
```bash
curl -X DELETE -H "Content-Type: application/json" http://localhost:10004/api/redis/keys/k1
```
### get key
```bash
curl -X GET -H "Content-Type: application/json" http://localhost:10004/api/redis/keys/k1
```
### get key list
```bash
curl -X GET -H "Content-Type: application/json" http://localhost:10004/api/redis/keys
```
