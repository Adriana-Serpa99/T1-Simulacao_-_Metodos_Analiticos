
## Trabalho T1 - Construir um simulador baseado em eventos ##


O simulador deve ser capaz de simular uma realidade com pelo menos três filas interligadas, com probabilidades de roteamento para uma das filas, para fora do sistema e/ou para a mesma fila. As filas devem poder ser especificadas para possuir múltiplos servidores, diferentes capacidades (finita ou
infinita) e diferentes tempos de chegada e atendimento.

O simulador deve conter as seguintes estruturas:
<li>geração de números pseudoaleatórios utilizando o Método da Congruência Linear;</li>
<li>deve ser informada a semente utilizada (X0), e outros parâmetros que se fizerem necessários;</li>
<li>controle de eventos, avanço do tempo, teste de fim da simulação;</li>
<li>disparo de rotinas de tratamento de eventos;</li>
<li>contabilização de perda de clientes nas filas (quando se fizer necessário); </li>
<li>e contabilização dos resultados de simulação.</li>

<br>

Além disso, você deve especificar:

<li>a definição dos componentes do estado das filas da realidade modelada (utilizando Notação de
Kendall);</li>
<li> a rotina de inicialização do simulador;</li>
<li> a rotina de tratamento de eventos.</li>

<br>
Para fins de validação do seu simulador, você deve entregar o resultado de simulação de um modelo
qualquer (a temática fica a sua escolha) que contenha pelo menos três filas interligadas, com
probabilidades de roteamento para uma das filas, para fora do sistema e/ou para a mesma fila. O modelo
não deve ser com filas em tandem. Ao final, os entregáveis desta primeira etapa são:<br><br>

<li>descrição da realidade a ser simulada;</li>
<li>arquivo (de entrada) contendo o modelo;</li>
<li>executáveis e explicação/instruções de uso do simulador;</li>
<li>código-fonte documentado do simulador (pelo menos dos algoritmos considerados
“importantes”);</li>


