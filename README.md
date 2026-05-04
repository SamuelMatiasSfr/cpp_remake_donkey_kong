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
- Sistema de ataque com martelo
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
- Compilador C++ como suporte a C++14 ou superior
- Biblioteca SFML
- IDE

> Para usuário de Windows (MinGW): cuidado com compatibilidade:
> 1. Veja a versão do GCC: `g++ --version`
> 2. Veja o modelo de exceção do GCC: `dir <caminho_do_mingw>\bin\libgcc_s*.dll`
> 3. Baixe a SFML com a mesma versão do GCC e o mesmo modelo de exceção

> Os arquivos `.vscode/` são úteis para usuários do VS Code, mas você pode precisar ajustar os caminhos do compilador e da SFML conforme sua instalação.

### Execução

1. Baixe e extraia o arquivo `.zip` do projeto
2. Importe o projeto na IDE de sua preferência
3. Adicione o diretório `SFML/bin` às variáveis de ambiente
4. Configure os diretórios da SFML no projeto:  
   - `SFML/include`  
   - `SFML/lib`
5. Vincule as bibliotecas:  
   - `sfml-graphics`  
   - `sfml-window`  
   - `sfml-system`  
   - `sfml-audio`    
6. Compile o arquivo `main.cpp`
7. Certifique-se de que os arquivos `.dll` da SFML (na pasta `bin`) estejam na mesma pasta do executável (`main.exe`). Copie-os para lá.    
8. Execute o arquivo `main.cpp`

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

### Martelo
- Ao pegar o martelo, você tem 8 segundos para utilizá-lo
- Pressione **Tecla X** para usar o martelo
- Usar o martelo redireciona o barril para outra posição, mas ele permanece visível na tela

### Dicas
- Pule sobre os barris para evitar colisões e perda de vidas
- Execute o jogo em modo janela, na resolução inicial, para evitar problemas de escala gráfica

---

## Telas do Jogo
Capturas de tela mostrando a interface e a jogabilidade do jogo.

### Tela Inicial
<img width="700" height="610" alt="image" src="https://github.com/user-attachments/assets/78238728-9c39-4f82-a448-843c6707b312" />

### Tela da Fase 1
<img width="800" height="664" alt="image" src="https://github.com/user-attachments/assets/89f52e7d-ea66-464c-91f1-f5735820c236" />

### Tela da Fase 2
<img width="800" height="664" alt="image" src="https://github.com/user-attachments/assets/87a48f2f-14da-4e96-b4bf-5bd02a4f934f" />

### Tela Game Over
<img width="700" height="610" alt="image" src="https://github.com/user-attachments/assets/c391ad28-85e5-4ce2-a6af-989b48857910" />