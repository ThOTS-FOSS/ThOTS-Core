<<<<<<< HEAD
# 🏫 Projeto: Metaheuristica em Timetable Universitário

## Resumo do projeto

Desenvolvimento de uma *engine* para formulação de quadros de horários dos IFG, utilizando metaheuristica desenvolvida do zero para fins de conclusão do curso de Ciências da Computação.

## Definindo Timetable

Área da ***Pesquisa Operacional*** que consiste em agendar eventos (encontro de atores) em um plano (normalmente quadro de horas/agenda). Trata-se de um problema **NP-Difícil** muito importante para as áreas de Logística e Matemática Computacional.

# Aplicação

## 📓 Funcionamento

1. Os dados utilizados são obtidos de uma tabela ***.xls*** contendo registros como, Professor, Turma, Disciplina, Turma X Disciplina.
2. A tabela é processada por um modulo Python que a quebra em diversos ***.csv***, processando os valores textuais em Classes.
  2.1. Após preenchidas, as classes são relacionadas em conjuntos bijetivos.
3. A *engine* computa uma solução ***S*** vazia, tal qual os horários de todos os objetos são zero.
4. A *engine* gera as soluções a partir de uma heurística inicial.
5. As soluções contabilizadas são tratadas em uma metageurística (a definir).
6. Após obtênção da solução desejada, os valores são exportados em ***.pdf*** contendo a tabela de todos os objetos contabilizados no processo (sala, turma, professor).

## 🚀 Tecnologias utilizadas
 - Microsoft Excel e Google Sheets - softwares de edição de planilhas para formulação dos dados de entrada.
 - Python - modulos de processamento de dados textuais/tabelados e exportações dos valores obtidos para documento portável.
 - C/C++ - desenvolvimento do **kernel** da aplicação, processamento dos dados (objetos) e execução das metaheuristicas.
[comment]: - Flutter (Dart) - framework para desenvolvimento front-end da aplicação através de GUI.

=======
# 🏫 Projeto: Metaheuristica em Timetable Universitário

## Resumo do projeto

Desenvolvimento de uma *engine* para formulação de quadros de horários dos IFG, utilizando metaheuristica desenvolvida do zero para fins de conclusão do curso de Ciências da Computação.

## Definindo Timetable

Área da ***Pesquisa Operacional*** que consiste em agendar eventos (encontro de atores) em um plano (normalmente quadro de horas/agenda). Trata-se de um problema **NP-Difícil** muito importante para as áreas de Logística e Matemática Computacional.

# Aplicação

## 📓 Funcionamento

1. Os dados utilizados são obtidos de uma tabela ***.xls*** contendo registros como, Professor, Turma, Disciplina, Turma X Disciplina.
2. A tabela é processada por um modulo Python que a quebra em diversos ***.csv***, processando os valores textuais em Classes.
  2.1. Após preenchidas, as classes são relacionadas em conjuntos bijetivos.
3. A *engine* computa uma solução ***S*** vazia, tal qual os horários de todos os objetos são zero.
4. A *engine* gera as soluções a partir de uma heurística inicial.
5. As soluções contabilizadas são tratadas em uma metageurística (a definir).
6. Após obtênção da solução desejada, os valores são exportados em ***.pdf*** contendo a tabela de todos os objetos contabilizados no processo (sala, turma, professor).

## 🚀 Tecnologias utilizadas
 - Microsoft Excel e Google Sheets - softwares de edição de planilhas para formulação dos dados de entrada.
 - Python - modulos de processamento de dados textuais/tabelados e exportações dos valores obtidos para documento portável.
 - C/C++ - desenvolvimento do **kernel** da aplicação, processamento dos dados (objetos) e execução das metaheuristicas.
[comment]: - Flutter (Dart) - framework para desenvolvimento front-end da aplicação através de GUI.

>>>>>>> f294cd65b131a9061bfe13872b8aecceb33a1be1
