# grpc_bidirectionalchatservice
This chat service contains a  chat server for one-to-one chatting  using gRPC Bi-directional streaming. 
commands to setup and used are :
1)go mod init grpcChatServer 
2)touch chat.proto 
3)protoc --go-grpc_out=require_unimplemented_servers=false:./chatserver/ --go_out=./chatserver/chat.proto
4)now create server.go and write and run the code 
5)create chatserver.go and import everything needed and write the code 
6)hit the command in server.go env PORT=5000 go run serevr.go
7)now hit go run client.go 
8)get new terminal and again hit go run client.go 
9)Chat bidirectionaly 
