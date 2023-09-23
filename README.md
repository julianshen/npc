Install
---
go install ./...

Usage
---
```
protoc --go_out=. --go_opt=paths=source_relative --gonpc_out=. pb/hello.proto --gonpc_opt=paths=source_relative
```
