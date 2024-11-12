# go-live

**go-live makes creating go comamndline tool faster and make it available for everyone**
- you can make your repo private share installation command with people you want to use your tool if you want only selective people to use your tool.
### installation:
```
go install github.com/LocaMartin/go-live@latest
```
### usage:
```
go-live <tool name>
```
### in case you want to setup your tool to use preveous go versions
```
go-live <tool name> -gv <go version>
```
### flag:
```
-h : print help message
-gv : go version as argument
-v : go-live version
-s : silent
```
### output:

```
[-] creating tool <tool name>
[-] latest go version available on offical go site gox.x.x
[-] latest git action availavle v@x
[-] seting up git action at <tool name>.github/workflows/release.yml
[-] setting up your tool
[-] creating directories & files needed for your tool
[-] created cmd and <tool name> directory created (main.go , VERSION, version.go) file inside cmd directory inside "<tool name>/cmd/<tool name>" directory
[-] created go.mod and README.md file in root directory of <tool name>
[-] your tool structure
 <tool name>
     |
     |_.github/workflows/release.yml
     |_cmd/<tool name>/main.go
     |_cmd/<tool name>/VERSION
     |_cmd/<tool name>/version.go
     |_go.mod
     |_README.md
[-] your tool is ready
[-] you can edit main.go to add custom functions
[-] you can install your tool using go install github.com/<your username>/<tool name>@latest
```
### output if used `-s` flag:

```
[-] your tool is ready
[-] you can edit main.go to add custom functions
[-] you can install your tool using go install github.com/<your username>/<tool name>@latest
```

### support:
### connect: