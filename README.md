# Aplicação
Nesse repositório (ainda em PT-BR) se encontra o código *drive* para o projeto.

## 📓 Funcionamento

1. Os dados utilizados são obtidos de uma tabela ***.xls*** contendo registros como, Professor, Turma, Disciplina, Turma X Disciplina. **IMPORTANTE:** utilizar o template em *data/*. 
2. A tabela é processada por um modulo Python que a quebra em diversos ***.csv***, processando os valores textuais em Classes. Após preenchidas, as classes são relacionadas em conjuntos bijetivos.
3. A *engine* computa uma solução ***S*** vazia, tal qual os horários de todos os objetos são zero.
4. A *engine* gera as soluções a partir de uma heurística inicial.
5. As soluções contabilizadas são tratadas em uma metageurística (a definir).
6. Após obtênção da solução desejada, os valores são exportados em ***.pdf*** contendo a tabela de todos os objetos contabilizados no processo (sala, turma, professor).

## 🚀 Tecnologias utilizadas
 - Microsoft Excel e Google Sheets - softwares de edição de planilhas para formulação dos dados de entrada.
 - Python - modulos de processamento de dados textuais/tabelados e exportações dos valores obtidos para documento portável.
 - C/C++ - desenvolvimento do **kernel** da aplicação, processamento dos dados (objetos) e execução das metaheuristicas.
