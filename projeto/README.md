# Folha de Pagamento

Este arquivo contém o refatoramento do projeto da Folha de Pagamento!

Foram utilizados os seguintes métodos para tratar os smells do código:

# Extract Class:

Este método serve para quando existe duas classes exercendo as mesmas funções, o Extract Class é usado para que uma classe faça o trabalho das duas. Simplificando seu código e deixando-o mais enxuto e compreensível. No código, o método foi usado na classe Empregado, que engloba as classes Horista e Assalariado.

# Strategy:

O Strategy é um padrão de projeto comportamental que permite que você defina uma família de algoritmos, coloque-os em classes separadas, e faça os objetos deles intercambiáveis. O padrão Strategy sugere que você pegue uma classe que faz algo específico em diversas maneiras diferentes e extraia todos esses algoritmos para classes separadas. Dessa forma, além de uma maior organização do código, este também ficará mais visuavelmente agradável e com mais fácil compreensão. No código, este padrão foi usado na Agenda de Pagamento, colocando a criação das Agendas Semanal e Mensal em classes separadas.

# Duplicidade de código:

É comum que ao programar algo grande, o programador precise reutilizar certa função ou parte do código, repetindo várias linhas iguais para funções diferentes, gerando um código duplicado. A ideia é fazer uma implementação que possa utilizar a mesma grade de código para as funções, deixando um código mais limpo e compreensível. Essa estratégia foi usada na classe Main e na classe Funções na função para adicionar um horista ou assalariado, como pode ser observado na comparação entre o código original e o código refatorado.
