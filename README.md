# Exercícios de Estrutura Switch em Java (`exer-switch-java`)

Projeto de estudos focado na prática da estrutura condicional de múltipla escolha (`switch-case`) em Java, abordando desde cenários básicos até desafios com regras de negócio e validações avançadas.

---

## 📁 Estrutura do Projeto

Os arquivos-fonte estão localizados no pacote `exercicios.SWITCH` dentro de `src/exercicios/SWITCH/`:

### Exercícios Práticos (Básicos a Intermediários)
1. **Posto de Combustível** (`_1PostoCombustivel.java` / `PostoCombustivel.java`)  
   Cálculo do valor total de abastecimento com base no tipo de combustível (Gasolina, Etanol, Diesel).
2. **Cardápio de Lanchonete** (`_2CardapioLanchonete.java` / `CardapioLanchonete.java`)  
   Seleção de produto e cálculo do valor total pela quantidade.
3. **Plano de Assinatura** (`_3PlanoAssinatura.java` / `PlanoAssinatura.java`)  
   Seleção de plano (Básico, Profissional, Premium) com desconto de 10% para contrato anual (12 meses).
4. **Estacionamento** (`_4Estacionamento.java` / `Estacionamento.java`)  
   Cobrança por hora de acordo com a categoria do veículo (Moto, Carro, Caminhonete) e taxa adicional após 5 horas.
5. **Loja de Roupas** (`_5LojaRoupas.java` / `LojaRoupas.java`)  
   Seleção de itens de vestuário com desconto progressivo de 15% para 3 ou mais peças.
6. **Calculadora Simples** (`_6CalculadoraSimples.java` / `CalculadoraSimples.java`)  
   Operações matemáticas (Soma, Subtração, Multiplicação, Divisão) com tratamento para divisão por zero.
7. **Frete por Região** (`_7FreteRegiao.java` / `FreteRegiao.java`)  
   Cálculo de taxa de frete por região geográfica do Brasil com isenção (frete grátis) para compras a partir de R$ 300,00.
8. **Ingresso de Cinema** (`_8IngressoCinema.java` / `IngressoCinema.java`)  
   Cálculo de ingressos (Inteira, Meia, VIP) com desconto de 5% para compras acima de 4 ingressos.
9. **Banho e Tosa Pet Shop** (`_9ServicoBanhoETosa.java` / `ServicoBanhoETosa.java`)  
   Uso de `switch` aninhado para definir preços baseados no serviço e no porte do animal (Pequeno, Médio, Grande).
10. **Sistema de Pedidos com Adicional** (`_10SistemaPedidosAdicional.java` / `SistemaPedidosAdicional.java`)  
    Seleção de sobremesa (Açaí, Sorvete, Milkshake) com acréscimo opcional de adicionais.

### Desafios (Regras de Negócio e Validações)
11. **Posto de Combustível - Desafio** (`_11PostoCombustivelDesafio.java`)  
    Validação de litros positivos, desconto para Cliente VIP e aplicação de cupom promocional.
12. **Cardápio com Entrega - Desafio** (`_12CardapioLanchoneteDesafio.java`)  
    Validação de quantidade mínima, cupom de desconto e cálculo de entrega (Retirada ou Delivery com frete grátis acima de R$ 60,00).
13. **Ingresso de Cinema - Desafio** (`_13IngressoCinemaDesafio.java`)  
    Validação de idade em relação à classificação indicativa, descontos cumulativos (Grupo e Clube VIP) e itens adicionais (Combo pipoca).

---

## 🚀 Como Executar

### Pré-requisitos
- **Java JDK 17** ou superior instalado.

### Via Terminal
1. Compile os arquivos para uma pasta de saída:
   ```bash
   javac -d out src/exercicios/SWITCH/*.java
   ```

2. Execute o exercício desejado informando a classe correspondente:
   ```bash
   java -cp out exercicios.SWITCH._1PostoCombustivel
   ```
   *(Substitua `_1PostoCombustivel` pelo nome de qualquer outra classe que deseja testar)*

### Pela IDE (IntelliJ IDEA / VS Code / Eclipse)
- Abra o projeto na sua IDE.
- Navegue até `src/exercicios/SWITCH/`.
- Abra a classe desejada e execute o método `main`.
