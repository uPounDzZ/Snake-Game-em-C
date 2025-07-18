==========================
  JOGO DA COBRINHA (C)
==========================

Descrição:
-----------
Este é um jogo da cobrinha (snake game) feito em linguagem C para rodar no terminal do Windows.
O jogador controla a cobrinha usando as setas do teclado, tentando comer os pontos (letra "c") sem bater nas paredes ou em si mesmo.
Cada ponto coletado aumenta o tamanho da cobra e a pontuação.

Requisitos:
------------
- Sistema operacional: Windows
- Compilador C (como GCC com suporte a Windows - Ex: MinGW ou TDM-GCC)
- Terminal como CMD ou PowerShell

Compilação:
------------
Para compilar o código, use o seguinte comando no terminal (PowerShell ou CMD):

    gcc -o cobrinha cobrinha.c

Isso irá gerar um executável chamado "cobrinha.exe".

Execução:
----------
Para rodar o jogo após compilar:

    ./cobrinha

ou

    cobrinha.exe

Controles:
-----------
- SETAS (↑ ↓ ← →): Movem a cobra
- ENTER: Seleciona opções no menu
- ESC: Sai do jogo

Modos:
-------
Ao iniciar, você verá um menu com as opções:

1. Jogar o jogo
2. Ver recordes
3. Tutorial
4. Sair do jogo

Recordes:
----------
Os recordes de pontuação são salvos automaticamente no arquivo:

    recordes.txt

Cada linha mostra a pontuação e o nome do jogador.

Avisos:
--------
- Este código foi feito para rodar em **Windows**. Não funciona corretamente em Linux ou macOS por depender de <windows.h> e <conio.h>.
- O terminal será redimensionado automaticamente ao iniciar o jogo.

Autor:
-------
Feito por: [SEU NOME AQUI]
