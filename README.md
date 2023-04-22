Grupo: Maria Theresa de Sousa Ferreira e Guilherme Costa e Silva.

Uma aplicação de e-commerce utiliza as classes Venda, ItemVenda, Produto, Carrinho e Cliente. Para garantir o bom funcionamento da aplicação, você foi designado para criar testes de integração para as classes mencionadas.

A partir dessa informação, crie cenários de teste de integração para os seguintes casos:

Adicionar um produto ao carrinho de compras

• O cliente adiciona um produto ao carrinho de compras

• O sistema atualiza o valor total do carrinho de compras

Finalizar uma venda

• O cliente finaliza a compra

• O sistema verifica se o carrinho de compras está vazio

• O sistema verifica se o cliente tem saldo suficiente para efetuar a compra

• O sistema atualiza o estoque dos produtos comprados

• O sistema registra a venda no histórico do cliente

• O sistema atualiza o saldo do cliente

Testar a busca de vendas por cliente:

• Verificar se é possível buscar as vendas de um determinado cliente

• Validar se as informações das vendas retornadas estão corretas, como a data e o valor total

• Verificar se todas as vendas do cliente são retornadas

Testar a busca de itens de venda por produto:

• Verificar se é possível buscar os itens de venda de um determinado produto

• Validar se as informações dos itens de venda retornados estão corretas, como a quantidade e o preço unitário

• Verificar se todos os itens de venda do produto são retornados

Para cada cenário, crie casos de teste que cubram todos os casos possíveis. Verifique se as classes estão funcionando corretamente e se os resultados obtidos estão de acordo com o esperado. Crie as classes services, repositories e controllers necessárias para a aplicação. Utilize JUnit e Spring Test para realizar os testes.

Proposta 02

Suponha que você esteja desenvolvendo uma aplicação financeira que precisa acessar a API do Banco Central para obter a cotação do dólar em um determinado dia. Para garantir que sua aplicação esteja funcionando corretamente, você precisa criar testes unitários e de integração para essa funcionalidade.

Teste a integração entre a sua aplicação e a API do Banco Central para obter a cotação do dólar em um determinado dia, com base nas seguintes regras:

Na primeira vez que for feita a busca para uma data, a cotação deve ser buscada na API e salva no banco de dados .Na próxima vez que for realizada uma busca para a mesma data, a cotação deve ser recuperada do banco de dados.

a) Teste a integração entre a sua aplicação e o banco de dados para persistir a cotação do dólar em um determinado dia.

b) Teste a recuperação da cotação do dólar em um determinado dia a partir do banco de dados.

Para realizar esses testes, você pode utilizar ferramentas como JUnit e Mockito para testes unitários e Spring Test para testes de integração. Além disso, você precisará criar mocks para simular as respostas da API do Banco Central durante os testes de integração. Você também deve criar as classes services, repositories e controllers necessárias para a aplicação.

Lembre-se de que, ao criar testes para acessar uma API externa, é importante considerar cenários de falhas na conexão ou na resposta da API e garantir que a aplicação esteja preparada para lidar com esses casos.
