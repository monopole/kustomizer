# kustomizer
Kustomize server


### Build
```
cd $GOPATH/src/github.com/monopole/kustomizer/pkg/helloworld
more helloworld.proto
rm helloworld.pb.go
protoc helloworld.proto --go_out=plugins=grpc:.
more helloworld.pb.go
```

### Run the server
```
cd $GOPATH/src/github.com/monopole/kustomizer   
go run cmd/kServer.go
```

### Run the client in another shell
```
cd $GOPATH/src/github.com/monopole/kustomizer
go run cmd/kClient.go
```
