
1. Export the path of the protoc-gen-go and protoc-gen-go-grpc
```shell
    export PATH="$PATH:$(go env GOPATH)/bin"
```

2. Script to build -
```shell
    protoc --proto_path=. --go_out=. --go-grpc_out=. user.proto
```
