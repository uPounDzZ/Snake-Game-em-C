# 🐍 Jogo da Cobrinha (Snake Game em C)

Um mini jogo da cobrinha feito em linguagem C, rodando direto no terminal do Windows (PowerShell). 

## 🛠 Requisitos

- Windows 10 ou superior
- [MinGW (GCC para Windows)](https://sourceforge.net/projects/mingw/)
- Terminal PowerShell

> ⚠ Este jogo usa bibliotecas específicas do Windows (`conio.h` e `windows.h`) e só funciona corretamente em terminais do próprio Windows.

---

## 🧩 Instalação do MinGW

1. Baixe o instalador: [mingw-get-setup.exe](https://sourceforge.net/projects/mingw/)
2. Na instalação, marque os seguintes pacotes:
   - `mingw32-base`
   - `mingw32-gcc-g++`
3. Aplique as mudanças (`Installation > Apply Changes`)
4. Adicione o caminho `C:\MinGW\bin` à variável de ambiente `Path`
5. Reinicie o PowerShell e digite:
   ```powershell
   gcc --version