## Trabalharemos com o que?
![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

* Esse projetinho faz parte de um curso lá da Udemy ![Udemy](https://img.shields.io/badge/Udemy-A435F0?style=for-the-badge&logo=Udemy&logoColor=white)

*Aqui está o Link do curso para os interessados
> : https://www.udemy.com/course/treina-dev-web-2023/learn/lecture/39781916#content

## Todos as Rotas
 

### Rota de Listagem de Todos os produtos

        http://localhost:3000/produtos

        Exemplo:

            {
                "nome": "PS1",
                "valor": 100
            }

### Rota de Listagem de Um único produto

    http://localhost:3000/produtos/1 __ou o valor unico de cada item__


    Exemplo:

        {
            "nome": "PS1",
            "valor": 100
        }

### Rota de Cadastro de um produto 

        http://localhost:3000/produtos

    Exemplo:

        {
            "id": 4, 
            "nome": "ps4",
            "valor": "2000"
        }

    > obs: NÃO ESQUEÇA DE COLOCAR O Body COMO JSON

### Rota de Deletar de um produto

    http://localhost:3000/produtos/1 __ou o valor unico de cada item__

    Exemplo:

        http://localhost:3000/produtos/4      

### Rota de Mudar o valor de um produto

    http://localhost:3000/produtos/1 __ou o valor unico de cada item__


    Exemplo:

        {
            "nome": "PS1",
            "valor": 100
        }
    
    > obs: NÃO ESQUEÇA DE COLOCAR O Body COMO JSON