Golang Fiber + React + VITE + Typescript
===

the repository code reference [youtube video](https://www.youtube.com/watch?v=QevhhM_QfbM)


### download source code
```
$ git clone https://github.com/KunYi/go-react-todo.git
```
### lunch server
```
$ cd go-react-to/server
$ go run main.go
```

### lunch client
```
$ cd go-react-todo/client
$ yarn install
$ yarn dev --host
```

---
# create project method (at Jan. 4 2023)

## prepare for server
```
# server side
$ mkdir go-react-todo
$ cd go-react-todo
$ mkdir server
$ cd sever
$ go mod init github.com/<your account>/go-react-todo
$ go get -u github.com/gofiber/fiber/v2
$ cd ..
```
## prepare for client
```
$ yarn create vite client -- --template react-ts
$ cd client
$ yarn add @mantine/hooks @mantine/core swr @primer/octicons-react
$ yarn add @emotion/cache @emotion/react @emotion/serialize @emotion/utils
```
