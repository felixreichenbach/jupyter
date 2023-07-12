# Gizmo

Looks like this is added: https://grpc-ecosystem.github.io/grpc-gateway/docs/tutorials/adding_annotations/

looks like it has the command to create the right proto files ```protoc -I . -I pb/google/api --go_out . --go_opt paths=source_relative --go-grpc_out . --go-grpc_opt paths=source_relative --grpc-gateway_out . --grpc-gateway_opt paths=source_relative ./pb/*.proto```


google apis -> https://github.com/googleapis/googleapis
https://github.com/googleapis/googleapis/blob/master/google/api/annotations.proto

brew install bazel

