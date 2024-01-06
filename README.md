# Instructor LED
## Import library

Setelah melakukan clone. Langkah selanjutnya adalah melakukan import libray yang digunakan seperti berikut:

1. go get
```shell
go get
```
2. go get github.com/gin-gonic/gin
```shell
go get github.com/gin-gonic/gin
```
3. go get github.com/joho/godotenv
```shell
go get github.com/joho/godotenv
```
4. go get github.com/lib/pq
```shell
go get github.com/lib/pq
```
5. go get github.com/golang-jwt/jwt/v5
```shell
go get github.com/golang-jwt/jwt/v5
```
6. go get github.com/sirupsen/logrus
```shell
go get github.com/sirupsen/logrus
```
7. go get golang.org/x/crypto/bcrypt
```shell
go get golang.org/x/crypto/bcrypt
```
8. go get github.com/DATA-DOG/go-sqlmock
```shell
go get github.com/DATA-DOG/go-sqlmock
```
9. go get github.com/stretchr/testify/assert
```shell
go get github.com/stretchr/testify/assert
```
10. go get github.com/stretchr/testify/mock
```shell
go get github.com/stretchr/testify/mock
```

## Config
Silahkan buat file baru dengan nama .env yang di duplikasi dari .env.example kemudian isi pada bagian berikut :
```shell
API_PORT=
DB_HOST=
DB_PORT=
DB_NAME=
USER=
PASSWORD=
DB_DRIVER=

LOG_FILE=logger.log
CSV_FILE=report.csv
TOKEN_LIFE_TIME=1 # jam
TOKEN_ISSUE_NAME=admin1@gmail.com # issuer bisa menggunakan username dari user
TOKEN_KEY=secret # key untuk token
```

Terdapat file ddl.sql dml.sql, silahkan buat database baru di postgre lalu import file tersebut

## Run
Jika sudah, jalankan program dengan perintah berikut :
```shell
go run .
```
