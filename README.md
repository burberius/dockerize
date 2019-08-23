# dockerize
Simple spring boot web application to test the dockerization with Docker build against jib.

## First build
```
docker history dockerize-docker
IMAGE               CREATED             CREATED BY                                      SIZE                COMMENT
d62f45d3b2d3        2 minutes ago       /bin/sh -c #(nop)  ENTRYPOINT ["java" "-cp" …   0B                  
1aeb098931e7        2 minutes ago       /bin/sh -c #(nop) COPY dir:57ab98bc3bd42e3e4…   3.04kB              
1a178457f5fa        2 minutes ago       /bin/sh -c #(nop) COPY dir:8d223655165f599f5…   3.02kB              
56bbc61e0ad2        2 minutes ago       /bin/sh -c #(nop) COPY dir:18fb9c090d58717dd…   18.8MB              
621e25a118b0        6 minutes ago       /bin/sh -c #(nop)  ARG DEPENDENCY=target/dep…   0B                  
2f6e2cbd1b79        6 minutes ago       /bin/sh -c #(nop)  VOLUME [/tmp]                0B                  
f1309e5e5c1f        49 years ago        bazel build ...                                 176MB               
<missing>           49 years ago        bazel build ...                                 1.93MB              
<missing>           49 years ago        bazel build ...                                 15.1MB              
<missing>           49 years ago        bazel build ...                                 1.82MB       ```
