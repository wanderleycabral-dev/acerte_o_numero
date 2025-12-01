# Acerte o Número

Um jogo simples de adivinhação de números desenvolvido em Rust, onde o jogador tenta descobrir um número secreto gerado aleatoriamente.

## 📋 Descrição

Este é um jogo de console interativo onde o programa gera um número aleatório entre 1 e 100, e o jogador deve tentar adivinhar qual é esse número. O jogo fornece feedback indicando se o palpite está muito alto, muito baixo ou correto.

## 🎮 Como Jogar

1. Execute o programa
2. Digite um número quando solicitado
3. O programa informará se seu palpite está:
   - **Muito baixo** - o número secreto é maior
   - **Muito alto** - o número secreto é menor
   - **Correto** - você acertou! O jogo termina

## 🚀 Como Executar

### Pré-requisitos

- [Rust](https://www.rust-lang.org/tools/install) instalado no seu sistema
- Cargo (gerenciador de pacotes do Rust, incluído na instalação do Rust)

### Compilar e Executar

```bash
# Compilar o projeto
cargo build

# Executar o projeto
cargo run

# Ou compilar e executar em um único comando
cargo run
```

### Compilar para Release

```bash
cargo build --release
```

O executável estará em `target/release/jogo_de_advinhacao` (ou `target/debug/jogo_de_advinhacao` para builds de debug).

## 📁 Estrutura do Projeto

```
jogo_de_advinhacao/
├── Cargo.toml          # Configuração do projeto e dependências
├── Cargo.lock          # Versões exatas das dependências
├── README.md           # Este arquivo
└── src/
    └── main.rs         # Código fonte principal
```

## 📦 Dependências

- **rand** (versão 0.4.0): Biblioteca para geração de números aleatórios

## 🔧 Funcionalidades

- Geração de número aleatório entre 1 e 100
- Validação de entrada do usuário
- Feedback em tempo real sobre o palpite
- Loop contínuo até acertar o número
- Tratamento de erros para entradas inválidas

## 👤 Autor

Wanderley Cabral

## 📝 Licença

Este projeto é um exemplo educacional e está disponível para uso livre.

# acerte_o_numero
