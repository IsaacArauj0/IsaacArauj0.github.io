# Projeto_ExtensaoI

O projeto consiste em um jogo sudoku digital para estimular o pensamento e treinar o raciocínio lógico. Direcionado tanto para o público infantil quanto para o público mais velho.

<h2> Histórico de Atualizações </h2>

<h3>v1 - v2</h3>

Sudoku.v2

Percebemos que não estava muito intuitivo para o usuário escolher as linhas e as colunas do sudoku que seriam preenchidas, levando em consideração que a numeração das linhas e das colunas começavam no 0, ou seja, se o usuário quisesse escolher a primeira coluna ou a primeira linha seria preciso digitar o número 0 invés do número 1.
Como isso não é intuitivo, e pensando em simplicar o uso para o usuário, criamos as variáveis 'row_def' e 'col_def' ('def' = definitivo).
O usario irá digitar o número referente a coluna e a linha que ele quer preencher, esse numero será guardado nas variáveis row e col.

Assim, row_def e col_def receberão:

row_def = row - 1; <br>
col_def = col - 1;

E o programa usará as variáveis 'row_def' e 'col_def' como parâmetros para executar o preenchimento do sudoku, dessa forma, quando o usuário quiser se referir a primeira linha, ele digitará 1 (row) e o código usará 0 (row_def) como parâmetro. A mesma coisa se aplicando a colunas (col).
