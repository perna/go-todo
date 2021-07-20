# Go Todo App

Criação de uma Todo list para fins educacionais utilizando Golang, MongoDB e React no Client. O código é baseado neste [Tutorial](https://levelup.gitconnected.com/build-a-todo-app-in-golang-mongodb-and-react-e1357b4690a6).

## Instruções
- Renomeie ou copie o arquivo `.env.example` para `.env`;
- Mude os parâmetros abaixo referentes à conexão com o MongoDB:
```
DB_URI="MONGO DB Connection string"
DB_NAME="test"
DB_COLLECTION_NAME="todolist"
```
- no diretório `server` execute o comando `go run main.go`. Se a mensagem abaixo for mostrada, o server está funcioando e aguardando conexões
```
Connected to MongoDB
Collection instance created
Starting server on the port 8080...
```
- no diretório `client` execute o comando `npm start`. Se a mensagem for igual a mensagem abaixo, seu client está funcionando e pode ser acessado via browser no endereço `http://localhost:3000/`
```
Compiled successfully!

You can now view client in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://172.21.214.174:3000

Note that the development build is not optimized.
To create a production build, use yarn build.
```

Print da App
![image](https://user-images.githubusercontent.com/1197591/126377616-da0ea165-1324-4799-bfc7-c1d808e0e73b.png)


Enjoy.

