# grpc model for microservices
Need to set CI/CD pipeline to generate model files

## Generate code for golang
```
protoc -I="$(pwd)" --go_opt=paths=source_relative --go-grpc_out=../golang/models/ticket/ --go-grpc_opt=paths=source_relative --go_out=../golang/models/ticket/ ticket.proto
```
