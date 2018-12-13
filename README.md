# srproxy
Get request proxy to.

### Installation:

```
npm i srproxy -g
```

### Usage:
Run proxy:
```
srproxy -s http://postman-echo.com/
```

Test it with `curl`:
```
curl http://0.0.0.0:9989/get?foo=bar
```


### Options: 

`-s, --server <server>` - Server to proxy request to. Default to `http://google.com`

`-h, --host <host>`     - Local hostname to listen on. Default to `0.0.0.0`

`-p, --port <port>`     - Local port to listen on. Default to `9989`
