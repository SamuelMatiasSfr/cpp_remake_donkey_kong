# Remake do Donkey Kong de Atari 

Jogo desenvolvido em C++ inspirado no jogo Donkey Kong de Atari, com o objetivo de reproduzir suas principais mecânicas de jogabilidade. Este projeto foi desenvolvido como trabalho prático da disciplina Linguagem e Técnicas de Programação 1 no curso técnico de informática do CEFET-MG, utilizando a biblioteca SFML para recursos gráficos e multimídia.

---

## Funcionalidades:
- Movimentação do personagem em plataformas
- Sistema de pulo e de subir escadas
- Sistema de ataques com martelo e escudo de proteção
- Inimigos e chefão por fase
- Sistema de colisão
- Sistema de vitória e game over

## Tecnologias usadas:
- C++
- SFML
- Eclipse IDE

---

## Requisitos
- **SFML**: Certifique-se de ter a biblioteca SFML (2.5.1 ou superior) instalada e configurada em seu ambiente de desenvolvimento
- **Compilador C**: Um compilador compatível com C++11 ou superior

## Como executar

1. Baixe e extraia o arquivo zip do projeto
2. Instale a SFML
   - Baixe a biblioteca SFML pelo site oficial: (https://www.sfml-dev.org/download.php)
   - Siga as instruções de instalação de acordo com seu sistema operacional

3. Configuração do Projeto
   - Abra sua IDE preferida e importe o projeto
   - Inclua os diretórios da SFML nas configurações de construção do projeto:
     - Adicione o caminho `SFML/include`
     - Adicione o caminho `SFML/lib`
     - Inclua as bibliotecas `sfml-graphics`, `sfml-window`, `sfml-system`, `sfml-audio`
     - Adicionar `SFML/bin;` as variaveis de ambiente da IDE
      
4. Execute o Jogo

---

## Como Jogar

### Objetivo
Resgate a princesa Pauline! Antes disso, colete todas as moedas disponíveis no local

### Controles
- **⬆️ Cima**: Subir escadas
- **⬇️ Baixo**: Descer escadas
- **⬅️ Esquerda**: Mover-se para a esquerda
- **➡️ Direita**: Mover-se para a direita
- **⏺ Espaço**: Pular

### Martelo
- Ao pegar o martelo, você tem **8 segundos** para utilizá-lo
- **Pressione `X`** para usá-lo
- Usar o martelo redireciona o barril para outra posição, mas ele permanece visível na tela

### Dicas
- É possível **pular sobre os barris** para evitar colisões
- Execute o jogo somente em modo janela
- Não utilize o modo tela cheia, pois pode ocorrer erro de escala gráfica


