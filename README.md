# sctp30

### gRPC service projects with protobuf and go


#### Prerequisite:
Make sure you have go, [protobuf](https://grpc.io/docs/protoc-installation/) compiler, and [mongodb](https://www.mongodb.com/docs/mongodb-shell/install/) installed on your machine. 
#### Setup:

You can easily run everything by first running ```make <appName>```. `<appName>` is the directory you want to setup e.g blog. 

Run ``make blog``. This with invoke `protoc`, which is a protobuf compiler that generates go code from the `.proto` files. This command also creates an executable binary which is located at `./bin/`. Use the binary to run the server and the client. 


