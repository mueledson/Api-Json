## Como eu usei os endpoints
* Usei o Insomnia

### Todos as Rotas
* Rota de Listagem de Todos os produtos

    ````
        http://localhost:3000/produtos
    ````

    Exemplo:

    ````
        {
            "nome": "PS1",
            "valor": 100
        }
    ````

* Rota de Listagem de Um único produto

    ````
        http://localhost:3000/produtos/1 __ ou o valor unico de cada item __
    ````

    Exemplo:

    ````
        {
            "nome": "PS1",
            "valor": 100
        }
    ````

* Rota de Cadastro de um produto 

    ````
        http://localhost:3000/produtos
    ````

    Exemplo:

    ````
        {
            "id": 4, 
            "nome": "ps4",
            "valor": "2000"
        }
    ````

    __ obs: NÃO ESQUEÇA DE COLOCAR O Body COMO JSON __

* Rota de Deletar de um produto

    ````    
        http://localhost:3000/produtos/1 |__ ou o valor unico de cada item __
    ````

    Exemplo:

    ````
        http://localhost:3000/produtos/4
    ````        

* Rota de Mudar o valor de um produto

    ````
        http://localhost:3000/produtos/1 __ ou o valor unico de cada item __
    ````

    Exemplo:

    ````
        {
            "nome": "PS1",
            "valor": 100
        }
    ````

    __ obs: NÃO ESQUEÇA DE COLOCAR O Body COMO JSON __