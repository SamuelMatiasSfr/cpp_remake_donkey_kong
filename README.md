# Remake do Donkey Kong de Atari 

Jogo desenvolvido em C++, inspirado no clássico Donkey Kong do Atari, com foco na recriação de suas principais mecânicas de jogabilidade.

O projeto foi desenvolvido como trabalho prático da disciplina Linguagem e Técnicas de Programação I, no curso técnico em informática do CEFET-MG, utilizando a biblioteca SFML para gerenciamento de recursos gráficos e multimídia.

## Status do Projeto

Projeto estável e pronto para uso.

Este projeto foi desenvolvido para fins acadêmicos e não está mais em manutenção. O projeto é mantido aqui como demonstração de conceito e aprendizado.

---

## Objetivos
- Praticar lógica de programação
- Aprender conceitos de Programação Orientada a Objetos (POO) em C++
- Aplicar conceitos de POO no desenvolvimento de jogos
- Recriar as principais mecânicas, regras e elementos visuais do jogo original
- Adquirir experiência no desenvolvimento de jogos utilizando a biblioteca SFML

## Funcionalidades
- Movimentação do personagem em plataformas
- Sistema de pulo e movimentação em escadas
- Sistema de ataque com martelo e escudo de proteção
- Sistema de controle de vidas
- Progressão entre fases
- Presença de inimigos e chefão por fase
- Sistema de detecção de colisões
- Sistema de condições de vitória e game over

## Tecnologias Usadas
- C++
- SFML
- Eclipse IDE

---

## Como Executar

### Requisitos
- Compilador C++  
- SFML

## Execução

1. Baixe e extraia o arquivo `.zip` do projeto
   
2. Instale a SFML
   - Acesse o site oficial: `https://www.sfml-dev.org/download.php`
   - Baixe a versão compatível com seu compilador
   - Siga as instruções de instalação para o seu sistema operacional

3. Configuração do Projeto
   - Importe o projeto na IDE de sua preferência
   - Adicione os diretórios da SFML nas configurações do projeto:
     - `SFML/include`
     - `SFML/lib`
   - Vincule as bibliotecas:
     - `sfml-graphics`
     - `sfml-window`
     - `sfml-system`
     - `sfml-audio`
   - Adicione o diretório `SFML/bin` às variáveis de ambiente
      
5. Compile e execute o arquivo `main.cpp`

---

## Como Jogar

### Objetivo
Resgate a princesa Pauline. Antes disso, colete todas as moedas disponíveis no local.

### Controles
- **⬆️ Cima**: Subir escadas
- **⬇️ Baixo**: Descer escadas
- **⬅️ Esquerda**: Mover-se para a esquerda
- **➡️ Direita**: Mover-se para a direita
- **⏺ Espaço**: Pular
- **Tecla X**: Atacar com martelo

### Martelo e Escudo
- Ao pegar o martelo, você tem 8 segundos para utilizá-lo
- Pressione **Tecla X** para usar o martelo
- Usar o martelo redireciona o barril para outra posição, mas ele permanece visível na tela
- Ao pegar o escudo, você não sofrerá dano por 5 segundos 

### Dicas
- Pule sobre os barris para evitar colisões e perda de vidas
- Execute o jogo em modo janela, na resolução inicial, para evitar problemas de escala gráfica


