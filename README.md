# RedisExample for testing

# Installing on Window/Linux
* [Window](#Installing-on-window)
* [Linux](#Installing-on-Linux)

## Installing on window
[Download](https://github.com/microsoftarchive/redis/releases)

1. Download the redis file on github `Redis-x64-3.x.zip`
2. Extract zip file
3. Go to redis directory
4. Create run.bat 
   ```
   redis-server.exe redis.windows.conf
   pause
   ```

## Installing on Linux
### Centos
```
sudo yum install redis
```
### Ubuntu
```
sudo apt install redis-server
```

## Starting the server
### Window
run bat file to start `run.bat`

### Linux
```
service redis-server start
```
or
```
sudo systemctl start redis
```

## Using redis-cli

### Window
run `redis-cli.exe`

### Linux
```
redis-cli
```

## Docker
[https://hub.docker.com/_/redis](https://hub.docker.com/_/redis)
