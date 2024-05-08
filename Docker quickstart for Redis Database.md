Redis is a source-available, in-memory storage, used as a distributed, in-memory key–value database, cache and message broker, with optional durability.

## Redis Database Construction

* [Sever Construction](#Sever-Construction)
* [Browser](#Browser)
* [Use in Programming Languages](#Use-in-Programming-Languages)


## Sever Construction

Install Docker environment.

Pull [Redis Docker Image](https://hub.docker.com/_/redis).

```
docker pull redis
```

Start the image and set up Port mapping.

```
docker run -p 6379:6379 --name some-redis -d redis redis-server --save 60 1 --loglevel warning
```

## Browser

Download [Redis Insight Installer exe](https://download.redisinsight.redis.com/latest/Redis-Insight-win-installer.exe).

Reference [Redis Insight Doc](https://redis.io/docs/latest/develop/connect/insight/).

## Use in Programming Languages

Reference [Redis Connection](https://redis.io/docs/latest/develop/connect/clients/).