# Calculadora_Simples

### Detalhamento superficial 📚
Esse projeto é uma calculadora simples utilizando apenas Console, onde primeiramente, é solicitado dois números para o usuário afim de informar o sistema quais números serão somados, subtraidos, multiplicados ou divididos, depois disso é mostrado para o usuário 4 opções, onde por meio de uma das opções escolhidas pelo usuário, é onde o sistema sabe qual operação será realizada. E por último, é mostrado os dois números digitados, a operação escolhida e o valor final da operação

### Detalhamento técnico 💻
Foi criado uma classe com o nome de Operacoes, onde dentro dessa classe, foram criados 4 métodos:
1. **Somar**
2. **Subtrair**
3. **Dividir**
4. **Multiplicar**

Onde todas as classes recebem dois parâmetros do tipo double
> double n1, double n2

e retornam esses dois parâmetros de acordo com a operação realizada. Esse é o fluxo básico dos cálculos feitos pelo programa

Após isso, usando um Console.WriteLine é solicitado dois números para o usuário e para coletar os dados foi utilizado um split para quebrar os dois números digitados e separados por espaço, assim atribuindo o valor 1 a primeira variavel e o valor 2 a segunda variável. Com os dois números capturados, foi utilizado novamente o Console.WriteLine para solicitar ao usuário a escolha de uma operação e para armazenar essa opção, foi criada uma variável option e usado um Convert.ToInt32 para transformar de string para int, ou seja, ao invés de capturar o texto "somar", "subtrair" etc, foi utilizado números para referenciar cada operação e assim na hora de fazer uma estrutura de controle ser mais simples para mostrar cada operação.

Com os números que sofrerão as operações e a escolha de qual operação será realizada, foi criado uma estrutura de controle if else onde cada operação foi validada e caso o usuário digite um número diferente de 1 a 4, é exibida uma mensagem para que o usuário digite um número válido

### Linguagem utilizada
- C#

### IDE utilizada
- Visual Studio
