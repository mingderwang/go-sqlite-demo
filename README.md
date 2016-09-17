CGO_ENABLED=0 GOOS=linux go build -a -installsuffix cgo -o main .
//won't work because of sqlite3
