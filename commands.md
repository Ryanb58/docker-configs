## Sometimes you need to run some sort of cli tool or command.

#### Run Redis-CLI:

```
docker run --rm -ti --name rediscli --net host redis:alpine /bin/sh
```