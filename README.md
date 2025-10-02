# node-posgresql-connection-pool-test
- nodejs: 16
- express: 4.x
- pg: 8.x

# Run
Run docker first,
```
docker-compose up -d

```

Run express server,
```
npm run start

```

# Test
```
ab -n 100 -c 20 http://localhost:3000/test-timeout/
```




