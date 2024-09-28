![Logos MCTI, CNPEM e ILUM](https://github.com/leticiaalmnunes/PCD---Boletim/assets/172425156/93c3eb13-410c-40c0-a412-7096187678a4)
<h1 align='center'> Arriscando a Matemática - Jogos Didáticos </h1>
<h3 align='center'> Jogos matemáticos desenvolvidos em Python visando o uso para divulgação da Ilum Escola de Ciência. </h3>


<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

## Colaboradores
[<img src="https://avatars.githubusercontent.com/u/172424835?v=4" width=115>](https://github.com/adrian24009)
[<img src="https://avatars.githubusercontent.com/u/172425313?v=4" width=115>](https://github.com/GabrielMartinsSousa)
[<img src="https://avatars.githubusercontent.com/u/172425731?v=4" width=115>](https://github.com/IzabelCarvalho)
[<img src="https://avatars.githubusercontent.com/u/97992533?v=4" width=115>](https://github.com/JVictor1604)
[<img src="https://avatars.githubusercontent.com/u/172425156?v=4" width=115>](https://github.com/leticiaalmnunes)
[<img src="https://avatars.githubusercontent.com/u/172425487?v=4" width=115>](https://github.com/lucasnsilva7)
[<img src="https://avatars.githubusercontent.com/u/172424981?v=4" width=115>](https://github.com/ClaraLelis)
[<img src="https://avatars.githubusercontent.com/u/171518829?v=4" width=115>](https://github.com/yasminbshimizu)

* Adrian Lincoln Paz Silva, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Gabriel Martins Sousa, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Izabel de Melo Carvalho, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* José Victor da Silva Izidório, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Letícia Almeida Nunes, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Lucas Nascimendo da Silva, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Maria Clara Macêdo Lelis, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Yasmin Barbosa Shimizu, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais

<br>

## Descrição do Projeto
O evento <b>*Ilum Portas Abertas (IPA)*</b> é uma iniciativa da <b>*Ilum Escola de Ciências*</b> para atrair possíveis ingressantes e divulgar as pesquisas e atividades realizadas na faculdade. Na edição 2024, uma dos stands é o "Arriscando a Matemática", que visa mostrar uma das formas como a matemática é ensinada na instituição e conta com as atividades *Cidade Dorme Criptografado*, *Mega Senha* e *Impostor*, jogos adaptados pelos Prof. Dr. Vinícius Wasques. Essa abordagem ativa torna o aprendizado mais lúdico e interativo, tornando o ensino de matemática mais atrativo e descontraído. <br>

Objetivando mostrar a interdisciplinaridade aplicada na Ilum, os alunos engajados na atividade decidiram usar métodos computacionais nos jogos **Cidade Dorme Criptografado** e **Mega Senha**. Portando, foram desenvolvidos códigos no Jupyter Notebook para decodificar as matrizes do Cidade Dorme Criptografado e no VSCode gerar o jogo e a interface do Mega Senha. Abaixo você encontrará as descrições e as regras dos jogos. <br>

## ÍNDICE
* [Colaboradores](#colaboradores)
* [Descrição do Projeto](#descrição-do-projeto)
* [Índice](#índice)
* [Arquivos](#arquivos)
* [Cidade Dorme Criptografado](#cidade-dorme-criptografado)
  - [Regras](#regras)
  - [Personagens](#personagens)
  - [Comandos](#comandos)
* [Mega Senha](#mega-senha)
  - [Regras](#regras)
* [Informações técnicas](#informações-técnicas)
* [Contribuições para o GitHub](#contribuições-para-o-github)
<br>

## Arquivos
**Nome do arquivo** - Conteúdo. <br>
*  **Arriscando a Matemática - IPA 2024 1** - Documento com as descrições das atividades que seriam realizadas no stand "Arriscando a Matemática".<br>
*  **Arriscando a Matemática - POSTERES e APRESENTAÇÕES** - Cartazes de divulgação, regras e imagens da interface do Mega Senha.<br>
*  **Cidade Dorme** - Matrizes com as chaves e personagens.<br>
*  **Conceitos Matemáticos 2** - Lista dos conceitos presentes no Mega Senha (pequenas alterações foram realizadas na transferência para o código).<br>

## Cidade Dorme Criptografado
Para descobrir qual personagem serão na atividade, os jogadores devem descriptografar a matriz sorteada com o auxíio do código fornecido.

Foram geradas matrizes **$M_{2X2}$** com algumas letras do personagem (*Exemplo: PESS = Pessoa*), em seguida cada letra foi "convertida" para seu respectivo número (A-Z, 0-26) e depois foram multiplicadas por uma matriz **$C_{2X2}$**(chave). Os jogadores recebem a matriz **$MC_{2X2}$** que resulta desse produto. Para conseguir descobrir a matriz original, precisam utilizar o código para multiplicar esta pela inversa da chave.

### Regras
Os jogadores só podem falar quando autorizados. <br>
Se o detetive descobrir quem é o assassino, pode decidir se vai contar ou não para os demais participantes.

### Personagens
**ASSA (Assassino)** – Mata 1 pessoa por rodada. <br>
**ANJO (Anjo)** – Salva 1 pessoa de ser morta por rodada.<br>
**DETV (Detetive)** – Tem 1 chance por rodada de descobrir o assassino.<br>
**CIVL (Civíl)** – Tenta descobrir quem é o assassino quando a cidade acorda.<br>
**PESS (Pessoa)** – Tenta descobrir quem é o assassino quando a cidade acorda.<br>
**ESTU (Estudante)** – Tenta descobrir quem é o assassino quando a cidade acorda.<br>

### Comandos
**Cidade dorme:** Todos fecham os olhos e baixam a cabeça.<br>
**Assassino acorda:** Apenas o assassino abre os olhos.<br>
**Assassino aponta para quem você quer matar:** O assassino aponta para a pessoa que quer matar.<br>
**Assassino dorme:** O assassino fecha os olhos.<br>
**Anjo acorda:** Apenas o anjo abre os olhos.<br>
**Anjo aponta para quem você quer salvar:** O anjo aponta para a pessoa que quer salvar.<br>
**Anjo dorme:** O anjo fecha os olhos.<br>
**Detetive acorda:** Apenas o detetive abre os olhos e aponta para a pessoa que acha que é o detetive. O mestre do jogo deve apenas balançar a cabeça afirmando ou negando se o palpite está correto.<br>
**Detetive dorme:** O detetive fecha os olhos.<br>
**Cidade acorda:** Todos abrem os olhos e levantam a cabeça.<br>
O mestre do jogo deve informar se alguém morreu (se sim, essa pessoa é eliminada) ou se a alguém foi salvo pelo anjo (sem dizer quem foi). Em seguida, os participantes têm 1 minuto para discutir. No fim do tempo, cada um deve apontar para quem acha que é o assassino. Se a maioria votar no assassino, o jogo acaba, senão, a pessoa mais votada é eliminada e o jogo continua. <br>
<br>

## Mega Senha
![3dfaab53-1a61-4afc-a3d3-573c720dc6e6](https://github.com/user-attachments/assets/6ff7565e-6a72-4598-a5cf-e01e721df4f0)

### Regras
Na tela, aparecerá um conceito matemático e uma dica sobre ele caso haja dúvidas. <br>
Sua missão é fazer o outro jogador acertar o conceito apenas com palavras-chave relacionadas ao tema!

* Só se pode dizer UMA palavra por vez.
* A cada palavra dita, deve haver um chute.
* Você pode pular 2 conceitos.
* É proibido reproduzir o conceito ou a frase da dica!

<br>

## Informações técnicas
* Linguagem de programação
  - Python 3.9
* Software
  - Jupyter Notebook
  - VSCode
* Bibliotecas
  - Pygame
  - Time
  - Random
<br>

## Contribuições para o GitHub
**CARVALHO, Izabel:** Arquivos
<br><br>
**DA SILVA, Lucas:** Código do Cidade Dorme
<br><br>
**IZIDÓRIO, José:** Código do Mega Senha
<br><br>
**LELIS, Maria:** Auxílio na estilização das interfaces dos códigos
<br><br>
**NUNES, Letícia:** Documentação
<br><br>
**SHIMIZU, Yasmin:** Design do Mega Senha
<br><br>
**SILVA, Adrian:** Código do Cidade Dorme
<br><br>
**SOUSA, Gabriel:** Seleção de áudios do Mega Senha e auxílio na descrição da atividade.
<br><br>
