## 🚀 25 Desafios de Controle de Fluxo em JavaScript (5 por Tópico)

### I. Condicionais: `if`/`else` e `if`/`else if`/`else`

1.  **Verificador de Idade e Acesso:**
    * Crie uma variável `idade` e uma variável `possuiAutorizacao` (booleana).
    * Escreva uma estrutura que verifique: se a `idade` for maior ou igual a 18 **OU** se a pessoa `possuiAutorizacao` for `true`, imprima `"Acesso Permitido"`. Caso contrário, imprima `"Acesso Negado"`.

2.  **Classificação de Triângulos:**
    * Crie três variáveis, `ladoA`, `ladoB`, e `ladoC`, representando os lados de um triângulo.
    * Use condicionais para determinar e imprimir o tipo de triângulo:
        * Se todos os lados forem iguais: `"Equilátero"`
        * Se apenas dois lados forem iguais: `"Isósceles"`
        * Se todos os lados forem diferentes: `"Escaleno"`

3.  **Sistema de Notas Escolar:**
    * Crie uma variável `nota` (de 0 a 100).
    * Use uma estrutura `if`/`else if`/`else` para imprimir a classificação:
        * `nota` maior ou igual a 90: `"A"`
        * `nota` entre 80 e 89: `"B"`
        * `nota` entre 70 e 79: `"C"`
        * Abaixo de 70: `"F"`

4.  **Verificador de Ano Bissexto:**
    * Crie uma variável `ano`.
    * Um ano é bissexto se for divisível por 4, **a não ser** que seja divisível por 100, mas **não** divisível por 400.
    * Use condicionais para determinar e imprimir se o `ano` é bissexto.

5.  **Semaforo Simples (Incorporado):**
    * Crie uma variável `corSemaforo` e atribua a ela uma string (`"vermelho"`, `"amarelo"` ou `"verde"`).
    * Use uma estrutura `if`/`else if`/`else` para imprimir a ação correta:
        * `"vermelho"` -> `"Parar"`
        * `"amarelo"` -> `"Atenção"`
        * `"verde"` -> `"Acelerar"`
        * Qualquer outra coisa -> `"Cor inválida"`

---

### II. Laços de Repetição: `for`

6.  **Contagem Crescente (Incorporado):**
    * Use um laço `for` para imprimir todos os números inteiros de 1 a 10 no console.

7.  **Soma de Números:**
    * Use um laço `for` para iterar de 1 a 100.
    * Mantenha uma variável de soma fora do laço e adicione cada número a ela.
    * Ao final, imprima o valor total da soma.

8.  **Números Pares e Ímpares em Intervalo:**
    * Use um laço `for` para iterar de 10 a 30.
    * Dentro do laço, use uma condicional (`if/else`) para imprimir se o número atual é `"Par"` ou `"Ímpar"`.

9.  **Percorrendo um Array de Strings:**
    * Crie um array chamado `frutas` com 5 nomes de frutas (ex: `"Maçã"`, `"Banana"`, etc.).
    * Use um laço `for` para iterar sobre o array e imprimir cada nome de fruta.

10. **Tabuada Dinâmica:**
    * Crie uma variável `numeroBase` e atribua um número (ex: 7).
    * Use um laço `for` para calcular e imprimir a tabuada desse número (de 1 a 10).
    * A saída deve ser: `"7 x 1 = 7"`, `"7 x 2 = 14"`, etc.

---

### III. Laços de Repetição: `while`

11. **Contagem Regressiva (Incorporado):**
    * Use um laço `while` para fazer uma contagem regressiva de 5 até 1.
    * Imprima o número em cada iteração.

12. **Cálculo de Fatorial:**
    * Crie uma variável `numero` (ex: 5) e uma variável `fatorial` inicializada em 1.
    * Use um laço `while` que calcule o fatorial do `numero`.
    * Ao final, imprima o resultado. (Ex: Fatorial de 5 é $5 \times 4 \times 3 \times 2 \times 1 = 120$).

13. **Verificador de Senha Simples:**
    * Crie uma variável `senhaCorreta` com um valor (ex: `"1234"`).
    * Crie uma variável `senhaTentada` com um valor diferente (ex: `"0000"`).
    * Use um laço `while` para simular tentativas. O laço deve continuar **enquanto** `senhaTentada` for diferente de `senhaCorreta`.
    * Dentro do laço, imprima `"Senha incorreta! Tente novamente."` e **simule uma nova tentativa** reatribuindo uma nova string diferente para `senhaTentada` a cada passo (faça isso manualmente para o exercício funcionar).

14. **Sorteio Simples (Incorporado):**
    * Crie uma variável `numeroAlvo` (por exemplo, 7).
    * Crie uma variável `tentativas` começando em 0.
    * Use um laço `while` que continua executando **enquanto** um número aleatório (gerado dentro do laço) não for igual ao `numeroAlvo`.
    * A cada iteração, incremente a variável `tentativas`.
    * Ao terminar, imprima quantas tentativas foram necessárias.

15. **Inversão de String (Caractere por Caractere):**
    * Crie uma variável `palavra` (ex: `"JavaScript"`).
    * Use um laço `while` para percorrer a string de trás para frente, construindo uma nova string invertida.
    * Imprima a nova string invertida.

---

### IV. Estrutura de Múltipla Escolha: `switch`

16. **Classificação de Dia da Semana (Incorporado):**
    * Crie uma variável `dia` e atribua um número de 1 a 7 a ela.
    * Use uma estrutura `switch` para imprimir o nome do dia correspondente (1 = Domingo, 2 = Segunda, etc.).
    * Se o número não estiver entre 1 e 7, imprima `"Dia inválido"`.

17. **Calculadora Básica:**
    * Crie três variáveis: `num1`, `num2` e `operacao` (ex: `"+"`, `"-"`, `"*"`, `/`).
    * Use uma estrutura `switch` no valor da variável `operacao` para realizar a operação matemática correta entre `num1` e `num2`.
    * Imprima o resultado. Inclua um `default` para `"Operação desconhecida"`.

18. **Nível de Permissão de Usuário:**
    * Crie uma variável `nivel` com um número (1, 2 ou 3).
    * Use um `switch` para imprimir a descrição do nível:
        * 1: `"Usuário Básico"`
        * 2: `"Usuário Editor"`
        * 3: `"Administrador"`
        * `default`: `"Nível de acesso não encontrado"`

19. **Mês por Nome:**
    * Crie uma variável `mes` (com um número de 1 a 12).
    * Use um `switch` para imprimir o nome do mês correspondente (1 = Janeiro, 2 = Fevereiro, etc.).

20. **Frutas e Seus Preços (Switch com Agrupamento):**
    * Crie uma variável `fruta` (string).
    * Use um `switch` para:
        * Para `"Maçã"` ou `"Banana"`, imprima `"R$ 3.00/kg"`.
        * Para `"Laranja"` ou `"Abacaxi"`, imprima `"R$ 5.50/kg"`.
        * Para qualquer outra fruta, imprima `"Produto não cadastrado"`. *Dica: Você pode agrupar `case`s.*

---

### V. Laços de Controle: `break` e `continue`

21. **Parar um Laço Cedo (`break`) (Incorporado):**
    * Use um laço `for` para iterar de 1 a 10.
    * Dentro do laço, use um `if` e a palavra-chave `break` para **parar** a execução do laço quando o número chegar a 7.
    * Imprima cada número antes de verificar a condição de parada.

22. **Encontrando um Valor em um Array:**
    * Crie um array `numeros` com 10 valores aleatórios.
    * Crie uma variável `alvo` (o número que você quer encontrar, ex: 42).
    * Use um laço `for` para percorrer o array. Assim que você encontrar o `alvo`, imprima `"Valor encontrado na posição X"` e use `break` para sair imediatamente.

23. **Pulando Iterações (`continue`):**
    * Use um laço `for` para iterar de 1 a 15.
    * Se o número for divisível por 4, use a palavra-chave `continue` para pular o resto do código do laço e ir para a próxima iteração.
    * Para todos os outros números, imprima o próprio número.

24. **Controle de Tentativas com `while` e `break`:**
    * Crie uma variável `maxTentativas` igual a 3 e um contador `tentativas` igual a 0.
    * Use um laço `while (true)` (laço infinito).
    * Dentro do laço:
        * Simule uma verificação de sucesso (ex: `if (tentativas === 2)`). Se for sucesso, imprima `"Sucesso!"` e use `break`.
        * Se não for sucesso, incremente `tentativas`.
        * Use um `if` para verificar se `tentativas` atingiu `maxTentativas`. Se sim, imprima `"Falha: Limite de tentativas atingido"` e use `break`.
        * *Dica: Você precisará imprimir alguma coisa a cada tentativa para ver o código rodando.*

25. **Pulando e Parando em Laço Simples:**
    * Use um laço `for` de 1 a 20.
    * Use `continue` para pular a impressão de qualquer número divisível por 3.
    * Use `break` para parar completamente o laço quando o número chegar a 17.
    * Imprima apenas os números que não foram pulados, até a parada.

---