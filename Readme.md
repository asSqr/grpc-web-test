### gRPC コマンド
`protoc --proto_path=protocol helloworld.proto --js_out=import_style=commonjs:./client/src/helloworld --go_out=plugins=grpc:./server/helloworld --grpc-web_out=import_style=typescript,mode=grpcwebtext:./client/src/helloworld`

### 参考
https://qiita.com/otanu/items/98d553d4b685a8419952