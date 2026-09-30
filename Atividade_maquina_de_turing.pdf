Etapa 1

1. O que é uma Máquina de Turing?

Uma Máquina de Turing é um modelo matemático abstrato, criado por Alan Turing, inspirado na máquina de escrever, que define o que é computação.

2. Quais são os principais componentes de uma Máquina de Turing?

Fita infinita, símbolos, cabeça de leitura, estados e transições.

3. Qual é a importância das Máquinas de Turing para a computação?

Máquinas de Turing definiram com rigor matemático o que é um programa e o que é computável, delimitando o paradigma de computação que usamos até hoje.

4. Qual é a relação entre Máquina de Turing e algoritmo?

Ela funciona como a descrição formal de um algoritmo, e as funções que podem ser expressas por ela são as chamadas funções computáveis.

Etapa 2


<img width="340" height="312" alt="Captura de Tela 2026-09-30 às 18 56 50" src="https://github.com/user-attachments/assets/785149ff-c683-432d-ab17-ee070f2bdd99" />




Etapa 3
Registro dos testes

Teste	     Entrada	    Resultado esperado	    Resultado obtido	                    Estados percorridos
1	          0011	           ACEITA	         ACEITA (fita final: XXYY)	     q0 > q1 > q2 > q0 > q1 > q2 > q0 > q3 > accept
2	          000111	         ACEITA	         ACEITA (fita final: XXXYYY)	   q0 > q1 > q2 > q0 > q1 > q2 > q0 > q1 > q2 > q0 > q3 > accept
3	          00111	           REJEITA	       REJEITA (fita final: XXYY1)	   q0 > q1 > q2 > q0 > q1 > q2 > q0 > q3 (para em q3)


teste 1 

<img width="1890" height="963" alt="Captura de Tela 2026-09-30 às 19 08 29" src="https://github.com/user-attachments/assets/ac668438-ccbb-4547-b81e-15700fa09c9f" />


teste 2 

<img width="1890" height="930" alt="Captura de Tela 2026-09-30 às 19 07 54" src="https://github.com/user-attachments/assets/90a70d68-bad2-44a2-b4e9-5bc3e6ed72d6" />


teste 3

<img width="1863" height="872" alt="Captura de Tela 2026-09-30 às 19 06 06" src="https://github.com/user-attachments/assets/d8d406af-74b2-49fd-bbc0-3ba450247647" />


Descrição da Máquina de Turing criada

A Máquina de Turing criada reconhece palavras da forma 0ⁿ1ⁿ. 
Ela funciona marcando os símbolos em pares: troca o primeiro 0 por X, avança para a 
direita até encontrar o primeiro 1 e o troca por Y, depois volta para a esquerda 
até o X e repete o processo.

 Etapa 4 — Reflexão sobre os limites computacionais

Uma Máquina de Turing não resolve qualquer problema. Ela resolve tudo o que é computável, mas existem problemas para os quais nenhum algoritmo funciona em 
todos os casos. O vídeo mostra isso ao explicar que existem funções e números computáveis e não computáveis, ou seja, a definição de Turing delimita o que dá para fazer e 
também o que não dá. O exemplo clássico é o Problema da Parada: decidir se um programa qualquer termina ou entra em loop infinito. Turing provou,
por contradição, que uma máquina capaz de decidir isso para todos os programas não pode existir. Além disso, há mais problemas do que algoritmos possíveis,
já que cada algoritmo é um texto finito que pode ser listado, e os problemas não. Esse é um limite da própria computação, e não da tecnologia: nem um computador quântico
faz algo que uma Máquina de Turing não faça, só faz mais rápido.

Questão final

Para saber se um problema é só difícil ou impossível de resolver, primeiro preciso separar dois conceitos. 
Um problema difícil tem solução: dá para criar um algoritmo, mesmo que ele demore muito ou use muita memória. 
Já um problema que não tem algoritmo é indecidível, e nenhuma Máquina de Turing consegue resolvê-lo para todos os casos.

Eu começaria tentando montar um algoritmo, mesmo que lento. Se der certo, o problema é computável e o desafio é só deixá-lo mais eficiente.
Se eu perceber que resolvê-lo também resolveria um problema já provado impossível, como o Problema da Parada, então ele também é indecidível. 
Nesse caso, nenhuma tecnologia futura vai resolver, porque nada computa além de uma Máquina de Turing.

