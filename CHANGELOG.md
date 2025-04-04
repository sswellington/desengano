# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),  
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- **Tabuleiro**
  - Implementação do tabuleiro **11x11x3** representando três níveis: subterrâneo, terrestre e aéreo.
  - Definição de **lanes** (Top, Bottom, Left, Right) e **jungle**.
  - Adicionadas **bases das equipes**:
    - `Ordem` (posição `10x0`) com borda **laranja**.
    - `Progresso` (posição `0x10`) com borda **verde-limão**.
  - Destaque visual para **diagonais**:
    - **Principal** em **amarelo**.
    - **Secundária** em **cor destacada**.
  - Adicionadas **torres** distribuídas nas lanes e diagonal secundária.
  - Inserção de **monstros** na jungle.

### Documents
- **Roteiro de Desenvolvimento** - Jogo MOBA/Card Game Folclórico.
- **Tabuleiro** - Estrutura e mecânicas principais.
- **Cartas** - (Em desenvolvimento).
- **Turnos** - (Em desenvolvimento).
