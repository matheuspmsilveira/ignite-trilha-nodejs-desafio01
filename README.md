## Requisitos a serem cumpridos

<h2>POST /users</h2>

- [x] A rota deve receber name, e username dentro do corpo da requisição. Ao cadastrar um novo usuário, ele deve ser armazenado dentro de um objeto no seguinte formato.

<h2>GET /todos</h2>

- [x] A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário e retornar uma lista com todas as tarefas desse usuário.

<h2>POST /todos</h2>

- [x] A rota deve receber title e deadline dentro do corpo da requisição e, uma propriedade username contendo o username do usuário dentro do header da requisição. Ao criar um novo *todo*, ele deve ser armazenada dentro da lista todos do usuário que está criando essa tarefa. Cada tarefa deverá estar no seguinte formato:  . Certifique-se que o ID seja um UUID.

<h2>PUT /todos/:id</h2>

- [x] A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário e receber as propriedades title e deadline dentro do corpo. É preciso alterar **apenas** o title e o deadline da tarefa que possua o id igual ao id presente nos parâmetros da rota.

<h2>PATCH /todos/:id/done</h2>

- [x] A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário e alterar a propriedade done para true no *todo* que possuir um id igual ao id presente nos parâmetros da rota.

<h2>DELETE /todos/:id</h2>

- [x] A rota deve receber, pelo header da requisição, uma propriedade username contendo o username do usuário e excluir o *todo* que possuir um id igual ao id presente nos parâmetros da rota.
