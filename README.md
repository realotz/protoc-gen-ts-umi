
下载并添加到环境变量

```golang
go get github.com/realotz/protoc-gen-ts-umi
```
生成
```bigquery
protoc --proto_path=.  --proto_path=./third_party --ts-umi_out=paths=source_relative:. test.proto
```