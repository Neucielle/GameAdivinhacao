### Exercício feito na aula da Alura + Oracle Next


# Jogo do Número Secreto
<p>Este é o jogo de adivinhação onde o objetivo é descobrir um número secreto gerado aleatoriamente entre 1 e 10.</p>

## Instruções
1. Ao iniciar o jogo, você verá a mensagem inicial indicando que você deve escolher um número entre 1 e 10.
2. Insira seu palpite no campo de entrada e clique em "Verificar".
3. O jogo irá te informar se o seu palpite está correto, se o número secreto é maior ou menor que o seu palpite.
4. Se você acertar o número secreto, o jogo irá mostrar a quantidade de tentativas que você levou para acertar e habilitará o botão de "Reiniciar" para você jogar novamente.
5. Se você errar, continue tentando até acertar o número secreto.

   
# Funções do Código
### Funções de Exibição
* exibirTextoNaTela(tag, texto): Exibe um texto em um elemento HTML especificado pela tag.
* exibirMensagemInicial(): Exibe a mensagem inicial do jogo.

  
### Funções de Verificação
* verificarChute(): Verifica se o palpite do jogador está correto, e dá feedback se o número secreto é maior ou menor. Também controla a contagem de tentativas.

### Funções Auxiliares
* gerarNumeroAleatorio(): Gera um número aleatório entre 1 e 10.
* limparCampo(): Limpa o campo de entrada para o próximo palpite.
* reiniciarJogo(): Reinicia o jogo, gerando um novo número secreto, limpando o campo de entrada e redefinindo a contagem de tentativas.

  
# Como Funciona
### Inicialização:

* O número secreto é gerado pela função gerarNumeroAleatorio().
* A mensagem inicial é exibida chamando exibirMensagemInicial().

  
## Jogando:

1. O jogador insere um palpite no campo de entrada.
2. O palpite é verificado pela função verificarChute(), que compara o palpite com o número secreto.
3. Se o palpite estiver correto, o jogador é informado e o botão de reiniciar é habilitado.
4. Se o palpite estiver incorreto, o jogador é informado se o número secreto é maior ou menor, e a contagem de tentativas é incrementada.
   
## Reiniciando:

* O jogador pode reiniciar o jogo clicando no botão de "Reiniciar", que chama a função reiniciarJogo().


# IMAGENS

![Opera Instantâneo_2024-07-01_155643_127 0 0 1](https://github.com/Neucielle/GameAdivinhacao/assets/116307577/8922af35-0c5e-4192-a9db-4e23a827e8ab)
![Opera Instantâneo_2024-07-01_155659_127 0 0 1](https://github.com/Neucielle/GameAdivinhacao/assets/116307577/d6de9adb-2465-4efe-99e6-897c6e1fe774)
![Opera Instantâneo_2024-07-01_155715_127 0 0 1](https://github.com/Neucielle/GameAdivinhacao/assets/116307577/e5000f0d-2cb2-4aff-8927-5503fec949ca)




