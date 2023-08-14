# go lightweight cobra template

## Customize template
- go through all files and rename go-cli-template with your project name
- adjust GO_VERSION in Dockerfile
- go version in go.mod

### Generate Markdown Documentation
```
make doc
```

### Using cobra cli

#### install
go install github.com/spf13/cobra-cli@latest

#### create new command
cobra-cli add <CMD_NAME>