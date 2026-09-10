De forma muito simples e direta:

* **Requisitos Funcionais:** Definem **O QUE** o sistema deve fazer. São as funcionalidades, as ações e os comportamentos esperados. Se você puder colocar um verbo de ação na frente (ex: "O usuário deve *poder fazer* X"), é um requisito funcional.
* **Requisitos Não Funcionais:** Definem **COMO** o sistema deve fazer. São os critérios de qualidade, desempenho, segurança, escalabilidade e usabilidade. Eles não são uma "funcionalidade" no qual você clica, mas sim a infraestrutura e a experiência por trás dela.

Para resumir: o Funcional resolve o problema do usuário; o Não Funcional garante que a solução não seja lenta, insegura ou instável.

---

## Exemplos Práticos (Aplicativo estilo iFood)

Aqui estão 3 exemplos de cada categoria para um aplicativo de delivery de comida:

### Requisitos Funcionais (O Que o app faz)

1. **Carrinho de Compras:** O sistema deve permitir que o cliente adicione, remova e altere a quantidade de itens no carrinho antes de fechar o pedido.
2. **Métodos de Pagamento:** O aplicativo deve processar pagamentos através de PIX, cartão de crédito e saldo na carteira (wallet).
3. **Gestão de Pedidos (Restaurante):** O painel do restaurante deve emitir um alerta sonoro e visual sempre que um novo pedido for recebido.

### Requisitos Não Funcionais (Como o app se comporta)

1. **Desempenho (Performance):** O cardápio do restaurante deve carregar na tela do usuário em, no máximo, **2 segundos** após o clique.
2. **Escalabilidade:** O sistema deve suportar até **50.000 pedidos simultâneos** em uma noite de sexta-feira sem apresentar lentidão ou quedas.
3. **Segurança:** Os dados de cartão de crédito dos usuários não podem ser armazenados em texto puro e todo o tráfego deve seguir os padrões de criptografia exigidos pelo Banco Central.

---

> **Dica de ouro:** A falta de um **Requisito Funcional** gera reclamações de que "o app não faz o que eu preciso". A falta de um **Requisito Não Funcional** gera reclamações de que "o app é lento, trava muito ou não é seguro".
