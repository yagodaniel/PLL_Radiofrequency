# PLL_Radiofrequency
## Tarefa desenvolvida para a disciplina de Circuitos de Radiofrequência, do curso de Engenharia Elétrica, UFERSA, Caraúbas, Brasil.
## Docente: Prof. Dr. Francisco de Assis Brito Filho
## Discentes: Jakson dos Santos Silva, José Ailton de Oliveira Júnior, Yago Daniel Souto
## Resumo
## Introdução
O Phase Locked Loop (PLL) é conhecido como Malha de Travamento de Fase, que no qual, faz parte de tecnologias referentes a transmissões sem fio, rádio e telecomunicações. O PLL é utilizado para demodulação FM, regeneração de sinais e sincronismos em transmissões digitais. Além disto, o PLL consisti em um sistema realimentado negativamente, que pode ser implementado de forma digital ou analógica, em que, para os digitais se trabalha em tempo discreto, utiliza-se filtros digitais e possuem detector de fase/frequência (PFD). Já os Analógicos são compostos geralmente por detector de fase (PD), filtro de malha e Osciladores Controlados por Tensão (VCO) que geram sinais senoidais. Contudo, os PLLs podem apresentar blocos mistos, digitais e analógicos, em que a principal razão para que eles possam ser classificados como digital ou analógico está na taxa de amostragem do sistema em relação a largura de banda (GUIMARÂES, 2015). <br />
Dessa forma, o princípio básico de funcionamento de um PLL está no ajuste contínuo da diferença entre as fases e/ou frequências presentes na entrada do loop. Na Figura 1 é visto um sistema básico de um PLL, em que esse sistema é composto por um detector de fase (PD) ou de fase/frequência (PFD), filtro de malha, VCO e um divisor de frequência. O PD ou PFD fornece uma tensão de controle que é proporcional a diferença de fase/frequência entre o sinal de referência e o sinal do VCO, de modo que, este sinal de controle passe por um filtro para que seja eliminado os componentes de alta frequência e, possa entra no VCO como uma tensão de controle do oscilador. O VCO apresenta em sua saída um sinal com uma frequência dependente da tensão de controle, que em seguida, esse sinal entra em um bloco divisor de frequência e realimenta o loop, como entrada do PD ou PFD. Com isso, a frequência de saída do VCO é uma multiplicação da frequência do sinal de referência, que quando ocorre uma alteração no sinal de referência a saída do VCO se adapta a nova frequência (GUIMARÂES, 2015).  <br />
#### Figura 1 – Esquemático básico de um PLL. Fonte: Autores, 2020.
## Implementação da tarefa
## TestBench
## Conclusões
## Trabalhos futuros
## Referências
ALMEIDA JÚNIOR, Paulo Acés de. PROJETO DE UM AMPLIFICADOR DE BAIXO RUÍDO E DE UM MISTURADOR DE FREQUÊNCIAS PARA UM TRANSCEPTOR ZIGBEE (2.4 GHz). TCC (Graduação) - Curso de Engenharia Eletrônica, Universidade de Brasília, Brasília, 2016. <br />
RAZAVI. RF Microelectronics. 2nd. Ed. 2011
