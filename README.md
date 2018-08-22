# Simple http 'hello world' for load balancer testing

Simple 'Hello world' in an HTTP server. (GET /) will return the current hostname.

## Running a simple test

`docker run --rm -it -p 80:80 strm/helloworld-http`

Will result in a single instance running on your port 80, you can test and will get a result like it: