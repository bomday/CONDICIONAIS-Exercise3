<h2>PROBLEM STATEMENT: Disputa de Pênaltis</h2>
---
<p>Com fim da fase de grupos e o início do mata-mata, vem junto com ele a possível etapa que testa o coração do brasileiro, a disputa de pênaltis. Nela, cada seleção bate pênaltis alternadamente e vence aquela que tiver mais gols que a adversária após ambas chutarem 5 pênaltis OU não ter mais como a outra seleção vencer a disputa, terminando instantaneamente a partida.</p>
<p>Exemplo: Na partida entre Croácia e Japão, a disputa terminou em 3 a 1 para Croácia, pois o Japão iria para o quinto e último chute e já não tinha mais chance virar o placar.</p>
<p>Sua missão será fazer a contagem de gols de uma disputa de pênaltis da copa e definir qual das seleções passa para próxima fase.</p>
<p>OBS: Caso as duas seleções façam seus 5 chutes e o resultado termine empatado, a disputa não continua nessa questão e considera-se apenas que ocorreu um empate.</p>
<h3>Input</h3>
---
<p>A entrada será formada primeiro pelo nome das duas seleções que estão disputando os pênaltis.</p>
- Nome1
<br/>
- Nome2
<br/><br/>
<p>Depois, virão 10 entradas, no máximo, já que podem vir menos se a disputa acabar antes, mas nunca mais que 10 entradas. As possibilidades de entradas são: “Gol”, “Errou”, “Na trave” e “Defendeu”, sendo que apenas a entrada “Gol” conta como gol para a seleção que bateu o pênalti. Além disso, as entradas de número ímpar são batidas pela seleção Nome1 e as entradas de número par batidas pela seleção Nome2.</p>
- EntradaX
<h3>Output</h3>
---
<p>Haverá apenas 2 possibilidades de saída. Caso uma das seleções vença a disputa, você imprimirá na tela:</p>
-> "{vencedor} vence a disputa de pênaltis por {gols_vencedor} a {gols_perdedor} e avança de fase!”
<br/><br/>
<p>Porém, caso haja um empate, a saída abaixo deverá ser mostrada:</p>
-> "Ambas as seleções terminaram com {numero_de_gols} gols, mas o desempate vai ficar para outro dia.”