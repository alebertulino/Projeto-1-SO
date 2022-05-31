# Projeto-1-SO

Objetivos
• Introduzir os conceitos de Processos (e seus estados);
• Familiarizar o estudante com conceitos de compilação em ambiente Unix;
• Aprimorar as capacidades de programação em Linguagem C e Programação 
Defensiva.
• Compreender o funcionamento dos algoritmos de escalonamento para Sistemas 
Operacionais.
Aspectos Gerais
Este projeto propõe ao estudante a implementação dos algoritmos de 
escalonamento para Sistemas Operacionais. O estudante deverá implementar o 
comportamento do algoritmo de escalonamento no formato de uma função em Linguagem 
C. A estrutura da função recebe alguns parâmetros a depender do tipo do algoritmo, esses 
parâmetros podem ser uma lista do tipo definido <Process>, o quanto o processo quer 
executar bem como outras informações.
Será fornecido ao estudante um código previamente construído com as estruturas 
de dados e simuladores de execução dos processos, requerendo do estudante se concentrar 
nos aspectos do algoritmo de escalonamento. A criação dos processos e simulação de sua 
execução já está previamente construída. Assim, o algoritmo na sua execução recebe como 
entrada um arquivo .txt que contém a criação dos processos, características e a simulação 
de sua execução.
Cada algoritmo de escalonamento é implementado dentro de uma biblioteca .h na 
linguagem C. Por exemplo, quando o estudante estiver implementando o algoritmo FCFS ele 
deverá codificar dentro do arquivo FCFS.h. Estes arquivos são incluídos dentro do programa 
principal em Linguagem C por meio da operação include.
Deverão ser implementados os seguintes algoritmos: 
• FCFS 
• RR 
• SJF
• Loteria
• SRTN
