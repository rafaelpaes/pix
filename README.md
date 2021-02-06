# pix


#Creating protobuffer
protoc --go_out=application/grpc/pb --go_opt=paths=source_relative --go_grpc_out=application/grpc/pb --go_grpc_opt=paths=source_relative --proto_path=application/grpc/protofiles application/grpc/protofiles/*.proto


#Evans
evans -r repl

#Cobra
cobra init --pkg-name codepix
