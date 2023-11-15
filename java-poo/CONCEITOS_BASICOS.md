**Exercícios sobre Bancos e Programação Orientada a Objetos (Java):**

Adicione os exercícios na pasta [exercicios](exercicios/).

### 1. **Classes e Objetos:**

   1.1 **Exercício Prático: Conta Bancária**

- Crie uma classe `ContaBancaria` com os atributos: número da conta, titular e saldo.
- Adicione métodos para depositar, sacar e verificar saldo.
- Instancie objetos dessa classe e teste os métodos criados.

1.2 **Desafio: Transações**

- Aprimore a classe `ContaBancaria` para incluir um histórico de transações.
- Cada transação deve ter uma descrição (depósito, saque) e o valor envolvido.
- Implemente um método para exibir o histórico de transações.

### 2. **Encapsulamento:**

2.1 **Exercício Prático: Conta Bancária Segura**

- Modifique a classe `ContaBancaria` para tornar os atributos privados e utilize métodos getters e setters.
- Garanta que o saldo não seja acessível diretamente, mas apenas por métodos específicos.

2.2 **Desafio: Conta com Limite**

- Adicione a capacidade de um limite de saque à classe `ContaBancaria`.
- Implemente um método que verifica se o saque é possível considerando o limite.

### 3. **Herança:**

3.1 **Exercício Prático: Conta Corrente e Conta Poupança**

- Crie duas classes, `ContaCorrente` e `ContaPoupanca`, que herdam da classe `ContaBancaria`.
- Adicione características específicas a cada tipo de conta (por exemplo, taxa de cheque especial para a conta corrente).

3.2 **Desafio: Transações Específicas**

- Modifique o histórico de transações para incluir informações específicas de cada tipo de conta.

### 4. **Polimorfismo:**

4.1 **Exercício Prático: Operações Polimórficas**

- Crie uma interface `OperacaoBancaria` com métodos como `executar` e `desfazer`.
- Implemente diferentes operações (depósito, saque) como classes que implementam essa interface.
- Aplique polimorfismo para executar diferentes operações em objetos do tipo `ContaBancaria`.

4.2 **Desafio: Histórico Polimórfico**

- Adapte o histórico de transações para armazenar objetos polimórficos da interface `OperacaoBancaria`.

### 5. **Abstração:**

5.1 **Exercício Prático: Banco Virtual**

- Crie uma classe `Banco` que contém uma lista de contas bancárias.
- Implemente métodos para realizar operações bancárias em diferentes contas sem expor detalhes internos.

5.2 **Desafio: Serviço de Notificação**

- Crie uma classe abstrata `ServicoNotificacao` com métodos como `enviarMensagem`.
- Implemente duas subclasses, uma para notificação por e-mail e outra por mensagem SMS.
- Integre o serviço de notificação à classe `Banco` para alertar titulares sobre transações importantes.

Estes exercícios visam solidificar os conceitos de programação orientada a objetos utilizando um cenário relacionado a bancos. Encoraje os desenvolvedores a adaptarem e estenderem esses exercícios para aprimorar ainda mais suas habilidades.
