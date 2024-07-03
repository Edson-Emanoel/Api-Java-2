### End Points

<img src="https://img.shields.io/badge/Codecov-F01F7A?style=for-the-badge&logo=Codecov&logoColor=white" />

![image]({"https://img.shields.io/badge/POST-298D46?style=for-the-badge"}) Cadastrar
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

![image]({"https://img.shields.io/badge/GET-792DE4?style=for-the-badge"}) Listar Todos
````
    http://localhost:8080/api/alunos/todos
````

![image]({"https://img.shields.io/badge/GET-792DE4?style=for-the-badge"}) Listar por Id
````
    http://localhost:8080/api/alunos/aluno/1
````

![image]({"https://img.shields.io/badge/DELETE-FF0000?style=for-the-badge"}) Remover
````
    http://localhost:8080/api/alunos/remover/2
````

![image]({"https://img.shields.io/badge/put-b9ffcf?style=for-the-badge&textColor=white"}) Alterar
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