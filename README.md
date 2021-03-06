## Instalação

- Execute os comandos abaixo na raiz do projeto


    php artisan db:create
    
    php artisan migrate
    


- Estes comandos criam o banco de dados e as tabelas necessárias para o funcionamento do webservice.
     
     
## Rotas

- Adiciona um novo cliente ou atualiza um cliente existente


    /adicionar-cliente

   
- Retorna um ou mais clientes de acordo com os parâmetros informados


     /buscar-cliente    

## Testes

Para facilitar os testes, importe a coleção do PostMan abaixo:
https://www.getpostman.com/collections/f9dda8651c9867961fd5
