# Operador && (AND) em C++

[![Status do Build](https://img.shields.io/badge/build-passing-brightgreen)](#)
[![Linguagem](https://img.shields.io/badge/C%2B%2B-100%25-blue)](#)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  

> Exemplo de uso do operador `&&` (AND) em C++  

---

## 🧾 Índice

- [Sobre](#sobre)  
- [Funcionalidades](#funcionalidades)  
- [Arquitetura / Estrutura](#arquitetura--estrutura)  
- [Como compilar / usar](#como-compilar--usar)  
- [Diagrama (Wokwi)](#diagrama-wokwi)  
- [Contribuição](#contribuição)  
- [Licença](#licença)  

---

## Sobre

Esse repositório demonstra um exemplo simples (ou didático) do uso do operador `&&` (AND) em C++.  
O foco é mostrar como funciona a avaliação lógica usando esse operador em um contexto básico.

---

## Funcionalidades

- Ilustração de comportamento do operador AND (`&&`)  
- Estrutura de código organizada em pastas (`src`, etc.)  
- Configurações de build com *PlatformIO*  
- Diagrama de circuito pronto para simulação no **Wokwi**  

---

## Arquitetura / Estrutura

```
├── .vscode/
├── src/
│ └── prog.ino (código fonte)
├── platformio.ini
├── wokwi.toml
├── diagram.json
└── .gitignore
```

- **src/prog.ino: código-fonte principal  
- **platformio.ini**: configuração do projeto embutido  
- **wokwi.toml**: configuração de simulação  
- **diagram.json**: circuito para abrir no Wokwi  

---

## Como compilar / usar

```
# Exemplo de comando (ajuste conforme seu setup)
platformio run

Ou, se for C++ puro:

g++ src/*.cpp -o meu_programa
./meu_programa
```

## Diagrama (Wokwi)

O projeto inclui um arquivo `diagram.json`, que pode ser aberto diretamente no [Wokwi](https://wokwi.com/projects/new/esp32) para visualizar e simular o circuito. Copie o conteúdo do arquivo `diagram.json` e cole na aba `diagram.json` no site Wokwi.

No VS Code, instale a extensão Wokwi for VS Code e clique com o botão direito em diagram.json → Reopen Editor with → Wokwi Diagram Editor.

## Contribuição

Contribuições são bem-vindas! Se quiser sugerir melhorias ou correções:

Faça um fork deste repositório

Crie uma branch com sua feature ou correção

Abra um pull request

## Licença

Este projeto está sob a licença MIT — veja o arquivo LICENSE para detalhes.

Made with ❤️ by m4ntonio
