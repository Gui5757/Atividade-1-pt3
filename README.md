# Atividade-1-pt3

fazer um desses

Implemente as seguintes melhorias na sua aplicação para reforçar os conceitos de REST:

    Adicione validação de campos: Implemente validação nos endpoints para garantir que os dados enviados possuem os campos obrigatórios e tipos corretos. Retorne um código de status 400 (Bad Request) quando a validação falhar.

    Implemente paginação: Modifique o endpoint GET /contatos para aceitar parâmetros de query ?page=1&limit=10, retornando apenas os registros solicitados.

    Adicione filtros REST: Crie um novo endpoint /contatos/buscar?nome=... para filtrar contatos por nome usando a API REST.

    Implemente tratamento de conflitos: No endpoint PUT ou PATCH, adicione validação para evitar sobrescrever dados e retorne 409 (Conflict) quando necessário.

    Adicione logging de requisições: Crie um middleware que registra em console cada requisição recebida (método, endpoint, status da resposta) para fins de debugging.

Desafio extra: Implemente autenticação básica (HTTP Basic Auth) em alguns endpoints, exigindo um token ou credencial simples.
