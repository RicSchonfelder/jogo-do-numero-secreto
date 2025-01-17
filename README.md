# Jogo do Número Secreto

![Jogo do Número Secreto](https://jogo-do-numero-secreto-lyart-ten.vercel.app/favicon.ico)

## Sobre o Projeto

O **Jogo do Número Secreto** é uma aplicação interativa e divertida desenvolvida para testar sua capacidade de adivinhar números. Com uma interface simples e direta, o jogo desafia você a adivinhar o número secreto gerado aleatoriamente dentro de um intervalo predefinido. O jogo é acessível diretamente em um navegador.

### Acesse o Jogo
**[Clique aqui para jogar agora!](https://jogo-do-numero-secreto-lyart-ten.vercel.app/)**

---

## Funcionalidades

- **Geração de número secreto aleatório**: O jogo escolhe um número entre 1 e 10 que você deve adivinhar.
- **Mensagens interativas**: O jogo informa se o número secreto é maior ou menor do que o número chutado.
- **Contador de tentativas**: Saiba quantas tentativas foram necessárias para adivinhar o número.
- **Reinício do jogo**: Após acertar, você pode reiniciar o jogo facilmente.
- **Feedback por voz**: Mensagens de voz utilizando a API `responsiveVoice` para maior imersão do jogador.

---

## Tecnologias Utilizadas

- **HTML**: Estrutura da página.
- **CSS**: Estilização básica para uma interface intuitiva.
- **JavaScript**: Lógica principal do jogo e interatividade.
- **responsiveVoice.js**: Biblioteca para síntese de voz.

---

## Estrutura do Código

### Variáveis Principais
- `listaDeNumerosSorteados`: Armazena os números já gerados para evitar repetições.
- `numeroLimite`: Define o limite superior do intervalo (10 no caso).
- `numeroSecreto`: Contém o número secreto gerado aleatoriamente.
- `tentativas`: Contador de tentativas do jogador.

### Funções

#### **exibirTextoNaTela(tag, texto)**
Exibe texto em um elemento HTML específico e utiliza a API de voz para anunciar o texto.

#### **exibirMensagemInicial()**
Exibe a mensagem inicial do jogo, com as instruções para o jogador.

#### **verificarChute()**
Lógica principal para verificar se o chute do jogador está correto, maior ou menor que o número secreto.

#### **gerarNumeroAleatorio()**
Gera o número secreto garantindo que ele não seja repetido em jogos consecutivos.

#### **limparCampo()**
Limpa o campo de entrada para facilitar a experiência do jogador.

#### **reiniciarJogo()**
Reinicia o jogo gerando um novo número secreto e restaurando o estado inicial.

---

## Como Executar o Projeto Localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/RicSchonfelder/jogo-do-numero-secreto.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd jogo-do-numero-secreto
   ```

3. Abra o arquivo `index.html` em um navegador:
   - No terminal:
     ```bash
     open index.html
     ```
   - Ou diretamente clicando no arquivo no seu gerenciador de arquivos.

---

## Contato

Para dúvidas ou sugestões, entre em contato:

- **GitHub**: [RicSchonfelder](https://github.com/RicSchonfelder)
- **Email**: [ricschonfelder@gmail.com](mailto:ricschonfelder@gmail.com)

---


Agradeço por conferir este projeto! Divirta-se jogando! 🎮

