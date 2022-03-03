# Note_Grpc_Golang
- Dowload Go: https://go.dev/dl/
- Create proto
- Go plugins for the protocol compiler:
1. Install the protocol compiler plugins for Go using the following commands:
- $ go install google.golang.org/protobuf/cmd/protoc-gen-go@v1.26
- $ go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@v1.1
2. Update your PATH so that the protoc compiler can find the plugins:
- $ export PATH="$PATH:$(go env GOPATH)/bin"

# Code
1. Update the gRPC service 
- https://grpc-ecosystem.github.io/grpc-gateway/docs/tutorials/adding_annotations/
2. Run Go install
- go get --> go install
- go install \
		google.golang.org/protobuf/cmd/protoc-gen-go \
		google.golang.org/grpc/cmd/protoc-gen-go-grpc \
		github.com/grpc-ecosystem/grpc-gateway/v2/protoc-gen-grpc-gateway \
		github.com/grpc-ecosystem/grpc-gateway/v2/protoc-gen-openapiv2
- 
