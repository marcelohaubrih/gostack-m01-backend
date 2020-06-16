## Criação do Projeto
- Instalado o express para utilização de rotas ($ yarn add express).
- Instalado o nodemon para verificação de alterações no projeto e automatizar a execução do serviço ($ yarn add nodemon -D)
- Instalado o uuidv4 ($ yarn add uuidv4)


## Middlewares
### Interceptador de requisições
 - Interrompo a requisição ou altera dados da requisição

## Métodos HTTP
 
 * GET: Buscar informações do back-end
 * POST: Criar uma informação no back-end
 * PUT/PATCH: Alterar uma informação no back-end
 * DELETE: Apagar uma informação no nack-end

## Tipos de parâmetros
 
 * Query Params: Filtros e paginação
 * Route Params: Identificar os recursos (Atualizar/Deletar)
 * Request Params: Conteúdo na hora de criar ou editar o recurso (Formulários - (JSON)).

## HTTP codes

### 1xx: Informational

### 2xx: Sucess
    - 200: SUCESS
    - 201: CREATED

### 3xx: Redirection
    - 301: Moved Permanently
    - 302: Moved

### 4xx: Client Error
    - 400: Bad Request
    - 401: Unauthorized
    - 404: Not Found

### 5xx: Server Error
    - 500: Internal Server Error