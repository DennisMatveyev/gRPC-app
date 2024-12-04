## Notations
- compilation command
    ```shell
    python -m grpc_tools.protoc --proto_path=protos --python_out=./pb --grpc_python_out=./pb --pyi_out=./pb protos/
    ``` 
- imports wrong because of usage of not standard dirs structure: https://github.com/protocolbuffers/protobuf/issues/1491
  make manual correction like -> `from . import ***_pb2`
