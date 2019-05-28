# golang-getting-start

## Go language 

### install 
   * [Getting Start Golang](https://golang.org/doc/install?download=go1.12.5.windows-amd64.msi)
            
### Setup Project
   * Create structure project
            
            D:
             |__Go
                 |__bin
                 |__pkg
                 |__src
                      |__<project1>
                      |__<project2>
                  
             =======================
             * GOPATH is D:\Go
             * GOROOT is C:\Go
             check environment command > go env 
             
### Install Go vendor
   * install govendor [kardianos/govendor](https://github.com/kardianos/govendor)
           
           go get -u github.com/kardianos/govendor
           
### Install Mockery
   * Install testify [stretchr/testify](https://github.com/stretchr/testify)
            
            go get github.com/stretchr/testify

    
