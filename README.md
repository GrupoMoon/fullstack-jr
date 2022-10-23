![ethinkers](./images/top-grupomoon.jpeg)

# Teste Full Stack - Grupo Moon

O teste consiste em criar um formulário de busca que irá consultar uma API REST do Magento2, a busca deverá ser feita no campo "customer_email". 

### Endpoint para consulta
https://dc98dbb.dizycommerce.com.br/index.php/rest/V1/orders/


### Credenciais para recuperar token Magento2
- User: testefullstack
- Senha: 8cjmbx1r


### Os resultados devem ser retornados em uma listagem com as seguintes colunas:

| customer_email                       | customer_firstname     | grand_total          |
|--------------------------------------|------------------------|----------------------|
| testefs@teste.com                    | Thiago                 | R$ 327,28            |
| testef2@teste.com                    | Rafael                 | R$ 252,00            |


### Paginar resultados de 15 em 15 registros.

-----

### Requisitos

- Criar um frontend para realizar a busca com uma UX elaborada
- Criar uma solução de autenticação entre o frontend e o backend
- Disponibilizar aplicação para utilizarmos e avaliarmos (Pode disponibilizar via git ou docker), documente no README como devemos executar.