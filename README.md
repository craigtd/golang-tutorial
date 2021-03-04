# Golang Tutorial
https://golang.org/doc/tutorial/

### Commands


When your code imports packages from another module, a go.mod file lists the specific modules and versions providing those packages. That file stays with your code, including in your source code repository.

To create a go.mod file, run the go mod init command, giving it the name of the module your code will be in 
```
go mod init hello
```

Run the go code in the current module
```
go run .
```

Use the following command to instruct Go to locate and download any package dependencies
```
go mod tidy
```


```
go build
```



### Syntax

In Go, a function whose name starts with a capital letter can be called by a function not in the same package. This is known in Go as an exported name. 
In Go, the := operator is a shortcut for declaring and initializing a variable in one line (Go uses the value on the right to determine the variable's type)
