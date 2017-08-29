# fw2-ncat
 Simple docker image for testing purposes

#### How to run
```
(HTTP_PORT=8080; docker run \
 --rm -it \
 -p $HTTP_PORT:$HTTP_PORT  \
 -e HTTP_PORT=$HTTP_PORT  \
 --name fw2-ncat amirandastratio/fw2-ncat)
```

#### How to test
```
> telnet localhost 8080
This is a test
```