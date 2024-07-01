# Bobr Protobuf

To compile Protobuf files we need these tools:

https://github.com/protocolbuffers/protobuf/releases/tag/v27.2
https://github.com/protocolbuffers/protobuf-go/releases/tag/v1.34.2
https://github.com/grpc/grpc-go/releases/tag/cmd%2Fprotoc-gen-go-grpc%2Fv1.4.0

### Command:

```shell
protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative tb.proto
```
