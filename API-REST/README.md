# API REST em PHP

Este é um projeto de API REST básico em PHP, que demonstra como estruturar um projeto utilizando com MVC, com controllers, models e configuração de rotas.

## Estrutura do Projeto

API-REST/   
Config/   
config.php   
Controller/   
API/   
BaseController.php   
UserController.php   
Model/   
Database.php   
UserModel.php   
database.json   
index.php   
README.md   


## Requisitos

- PHP 7.4 ou superior
- Composer 
- POSTMAN

# Configure seu servidor web para apontar para a pasta API-REST. Se estiver utilizando o servidor embutido do PHP, execute:

php -S localhost:8080

# Uso

Endpoints   
GET /api-rest/api/v1/user/list?limit=10   
Retorna uma lista de usuários com um limite especificado.   

# Exemplo de Requisição

Para listar os usuários, utilize a seguinte URL no Postman ou em seu navegador:

http://localhost:8080/api-rest/api/v1/user/list?limit=10
