## Trabalharemos com o que?
![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

### Todos as Rotas
 

* Rota de Listagem de Todos os produtos

        http://localhost:3000/produtos

        Exemplo:

            {
                "nome": "PS1",
                "valor": 100
            }

* Rota de Listagem de Um único produto

    http://localhost:3000/produtos/1 __ou o valor unico de cada item__


    Exemplo:

        {
            "nome": "PS1",
            "valor": 100
        }

* Rota de Cadastro de um produto 

        http://localhost:3000/produtos

    Exemplo:

        {
            "id": 4, 
            "nome": "ps4",
            "valor": "2000"
        }

    > obs: NÃO ESQUEÇA DE COLOCAR O Body COMO JSON

* Rota de Deletar de um produto

    http://localhost:3000/produtos/1 __ou o valor unico de cada item__

    Exemplo:

        http://localhost:3000/produtos/4      

* Rota de Mudar o valor de um produto

    http://localhost:3000/produtos/1 __ou o valor unico de cada item__


    Exemplo:

        {
            "nome": "PS1",
            "valor": 100
        }
    
    > obs: NÃO ESQUEÇA DE COLOCAR O Body COMO JSON