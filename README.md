Ethermint 官方版本由于不再维护, 使用的 tendermint 依赖停留在了 v0.14.0. 因此 Fork 出一份自己维护, 现已升级至 v0.17.1.

# 如何使用?

克隆项目, 并设置 GOPATH 为项目根目录.

```sh
go install ethermint/cmd/ethermint
go install github.com/tendermint/tendermint/cmd/tendermint
```
