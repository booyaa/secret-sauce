# juicy fruit

building and release go binaries on different platforms:

```sh
GOOS=___ GOARCH=___ go build -o juicy-fruit-macos-arm64 main.go
```

where GOOS and GOARCH are:

- Linux amd64 `GOOS=linux GOARCH=amd64`
- Windows amd64 `GOOS=windows GOARCH=amd64`
- MacOS amd64 `GOOS=darwin GOARCH=amd64`
- MacOS arm64 `GOOS=darwin GOARCH=arm64`