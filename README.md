go mod init <your_project_name>

---

// gin framework
go get -u github.com/gin-gonic/gin

// ORM library
go get -u github.com/jinzhu/gorm

// package that we will be used to authenticate and generate our JWT
go get -u github.com/dgrijalva/jwt-go

// to help manage our environment variables
go get -u github.com/joho/godotenv

// to encrypt our user's password
go get -u golang.org/x/crypto

---

questions:

1 - what is this structure?  How can I create one like this?

```go
gin.H{"data": "hello from controler"}
```