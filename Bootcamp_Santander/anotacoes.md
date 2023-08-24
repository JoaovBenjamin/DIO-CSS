 O CSS é formado por seletores e atriutos

 Para deixar mais especifico qual tag vc quer estilizar, utiiza o ID ou Classe. Lembrando que temos que ter apenas um ID na pagina.

 BOX Model:

 margin: espaçamento entre os elementos
 border: circulam a o padding e o content
 padding: espaçamento interno, entre a borda e o conteudo
 content: é o conteudo da caixa

Padding e Margin

 Quando o padding ou o margin se encontra assim:

.post{
    padding: 10px 5px
}

o 10px é o espaçamento superior e inferior
Já o 5px é o espaço nas laterais

 Quando o padding ou o margin se encontra assim:

.post{
    padding: 10px 5px 10px 5px
}

Nesse modelo os estilizadores vão funcionar como um relegio
10px é em cima, 5px na direita, 10px em baixo e 5 px na esquera.