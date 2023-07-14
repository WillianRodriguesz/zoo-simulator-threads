<h1 align="center"> 🦒🐵 Simulação de rotina de um zoológico usando threads 🦁🐻 </h1>

<p align="center">
Projeto desenvolvido na cadeira de programação de sistemas onde consiste em simular a rotina completa de um zoológico, que inclui a exibição dos animais ao público, a entrega diária de alimentos e os cuidados necessários de cada animal realizados pelo veterinário, e o abastecimento do estoque de comida do zoológico realizado por um fornecedor externo. A simulação foi desenvolvida considerando as características mencionadas e utilizando o conceito de threads para garantir a sincronização e a concorrência de processos.
</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>


## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- Python
- Jupyter
- LiveShare

## 💻 Projeto

Este projeto consiste em uma simulação da rotina diária de animais em um zoológico, utilizando threads. A simulação considera diversos aspectos, como a exibição dos animais, a alimentação fornecida por um fornecedor exclusivo e os cuidados realizados pelos veterinários. Algumas características importantes incluem:

- Cada animal segue um ciclo de exibição, alimentação e sono.
- Três espécies de animais são consideradas: leões, suricatos e avestruzes, cada um com suas preferências alimentares e tempo de sono.
- O tempo de sono para cada animal é determinado aleatoriamente dentro dos limites estabelecidos.
- A simulação é executada em uma escala de tempo onde uma hora do dia equivale a um segundo de execução.
- Os comedouros têm uma capacidade total de 10 unidades de alimento, e cada animal consome quantidades diferentes durante a alimentação.
- Os veterinários são responsáveis por manter os comedouros sempre abastecidos, retirando a comida de um estoque interno.
- A quantidade de animais, veterinários e fornecedores é definida, e o estoque do zoológico pode ser reabastecido por um fornecedor externo.
- O programa exibe na tela todas as atividades que ocorrem durante a simulação e, ao final, apresenta o consumo total de alimento por cada animal.
- O programa deve evitar e/ou detectar situações de deadlock (bloqueio) e starvation (inanição).
- Análises podem ser feitas em relação à execução do programa, considerando o número de animais, veterinários e fornecedores, bem como a equilibrada alimentação dos animais.

A simulação do zoológico é uma oportunidade para explorar conceitos como inanição, avaliar a disparidade dos resultados e considerar o impacto do número de animais, veterinários e fornecedores na execução do programa.

- [Acesse o projeto finalizado, online](https://colab.research.google.com/drive/1QPP4Rmb06kEd177M2shD_j4sf71eA7l-?usp=sharing)

## 🔖 Layout

Como o algoritmo foi desenvolvido em Python 3 e utilizando o Jupyter, basta clicar no botão de execução do Google Colab.
O resultado em tempo real pode ser acompanhado no terminal de execução, e 2 arquivos de log “animais.txt” e “veterinarios.txt” são gerados com dados após a finalização das threads.


## 👥 Colaboração

Este projeto está aberto a contribuições e colaborações da comunidade. Se você encontrar algum problema, tiver ideias para melhorias ou quiser adicionar novos recursos, sinta-se à vontade para fazer um fork deste repositório, fazer as alterações desejadas e enviar um pull request.

Agradeço antecipadamente a sua colaboração e estamos ansiosos para construir algo incrível juntos!



