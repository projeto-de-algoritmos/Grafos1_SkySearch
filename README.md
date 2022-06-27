# Grafos1_MouseCheese
O trabalho é uma demonstração de como a BFS e a DFS funcionam de forma visual. 

# Alunos

Aluno   | Matrícula
--------- | ------
Luan Vasco Cavalcante | 190111836
Sávio Cunha de Carvalho | 180130889

# Sobre
 O objetivo do projeto é demonstrar como a DFS() e a BFS() funcionam de forma visual.
 Ao final, quando a busca encontra o endpoint a BFS() desenha a menor rota de um ponto ao outro,ou seja, do gato ao rato.
 O objetivo foi atingido tratando a malha quadriculada como um grafo onde cada quadrado seria um nó.
 O projeto funciona de forma simples, um menu é apresentado e algumas opções são dadas : 

Nível   | Número de linhas
--------- | ------
Easy | 10
Medium | 25
Hard | 50

Além disso é fornecido uma opção onde o usuário escolhe se quer rodar uma BFS ou uma DFS. 
É possível voltar ao menu ao apertar a tecla 'm' e também é possível limpar a malha para redesenhar ao apertar 'c'.
Ao apertar Quit, o jogo se encerra.

# Screenshots

# Instalação
Linguagem : Python 3
Framework : Foi usado 2 bibliotecas principais para criação do jogo
  - pygame
  - pygame-menu
  
Clone o repositório com o comando :
git clone https://github.com/projeto-de-algoritmos/Grafos1_MouseCheese.git

Entre na pasta clonada:
cd Grafos1_MouseCheese

Em seguida instale as bibliotecas :
pip install -r requirements.txt

Execute o código :
python3 mouse_search.py

# Uso 
Ao escolher as opções descritas na seção sobre, uma malha quadriculada aparecerá e você deve seguir os seguintes passos:
1° clique : posiciona o rato
2° clique : posiciona o queijo
3° clique(s) : posiciona as barreiras (ao clicar e arrastar pode ficar mais fácil)
4° clique(s) com o botão direito do mouse : torna aquele quadrado vazio novamente (útil quando a passagem é fechada).

#Outros 
O código foi adaptado da implementação do encontrada no canal TechWithTim.
Link : https://www.youtube.com/watch?v=JtiK0DOeI4A
