### End Points

<img src="https://img.shields.io/badge/POST-298D46?style=for-the-badge" /> <span><h3>Cadastrar</h3></span>

````
    http://localhost:8080/api/alunos/cadastrar
````
* Body 
````
    {
        "nome": "Marcos Felipe",
        "serie": "9º E",
        "sexo": "M" 
    }
````

<span> <img src="https://img.shields.io/badge/put-FCFF3A?style=for-the-badge" /> <h3>Alterar</h3></span>

````
    http://localhost:8080/api/alunos/alterar/3
````
* Body
````
    {
        "id": 1,
        "nome": "Ana Beatriz",
        "serie": "9º A",
        "sexo": "F" 
    }
````

<span> <img src="https://img.shields.io/badge/GET-3217EA?style=for-the-badge" /> <h3>Listar Todos</h3></span>

````
    http://localhost:8080/api/alunos/todos
````

<span> <img src="https://img.shields.io/badge/GET-3217EA?style=for-the-badge" /> <h3>Listar por Id</h3></span>

````
    http://localhost:8080/api/alunos/aluno/1
````

<span> <img src="https://img.shields.io/badge/DELETE-FF0000?style=for-the-badge" /> <h3>Remover</h3></span>

````
    http://localhost:8080/api/alunos/remover/2
````