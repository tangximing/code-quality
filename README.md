# 代码质量
对于日常开发中代码质量把控的工具整理

## hooks
### pre-commit
* 使用方法：放入对应项目的.git/hooks/pre-commit，在git commit执行时自动完成
* 依赖项：
    * gofmt: go自带
    * goimports: go get -u golang.org/x/tools/cmd/goimports
    * golangci-lint: go get -u github.com/golangci/golangci-lint/cmd/golangci-lint/...
    * gocognit: go get github.com/uudashr/gocognit/cmd/gocognit
