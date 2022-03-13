# Treinamento-12-03-2022
 studos 2022

- Analisando o código acima:

- list-style-type: Esta prorpiedade é usada para alterar o marcador dos itens da lista. Os valores são diferentes para os tipos de listas. Os valores possíveis para listas ordenadas são:

- disc (padrão) - representação visual 
- circle - representação visual 
- square - representação visual 
- Há diversos valores para listas numeradas, porém, os mais usados são:

- decimal - numeração (1,2,3,4,...)
- lower-roman / upper-roman - sequência de caracteres romanos em caixa baixa/ALTA (i, ii, iii / I, II, III)
- lower-alpha / upper-alpha - sequência de caracteres arábicos em caixa baixa/ALTA (a,b,c / A,B,C)
- Percebemos que o atributo <li> do HTML é o mesmo para as duas lista, logo teríamos um problema para formatar os itens de uma tabela com cor vermelho e na outra tabela em cinza.

- Para resolver este problema, usamos uma estratégia bastante elegante e perfeitamente aceita em CSS, o encadeamento.

- ul: formata apenas a lista ordenada

- ol: formata apenas a lista numerada

- ul li: formata os itens da lista ordenada

- ol li: formata os itens da lista numerada
