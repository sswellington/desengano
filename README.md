# Desengano

Descrição:
🚀 MOBA/Card Game baseado no folclore brasileiro 🎴⚔️
Um jogo que mistura estratégia de MOBA com mecânicas de cartas, onde os jogadores controlam heróis inspirados no folclore brasileiro. O tabuleiro é um grid 11x11x3, com diferentes terrenos e objetivos estratégicos.

📌 Principais Características:
    Tabuleiro 11x11x3 com camadas subterrâneas, terrestres e aéreas.

    Divisão em lanes e jungle, com torres e monstros neutros.

    Duas equipes: Ordem e Progresso, cada uma buscando chegar à base inimiga.

    Heróis baseados no folclore brasileiro, cada um com habilidades únicas.

    Sistema de turnos e cartas para influenciar o combate e estratégia.

🔧 Tecnologias utilizadas:
    HTML, CSS e JavaScript puro (sem bibliotecas externas).

🌟 Status: Em desenvolvimento.

📌 Futuramente:

    Implementação de heróis jogáveis.

    Sistema de combate e habilidades.

    Mecânica completa de cartas e buffs/debuffs.

---

# 🏆 Tabuleiro 11x11x3 - MOBA + Card Game

Este é o tabuleiro do jogo em desenvolvimento, combinando mecânicas de **MOBA** e **jogos de cartas**. Ele representa um grid **11x11x3**, onde o terceiro valor (`z`) define o nível do terreno:

- `1` - **Subterrâneo** 🕳️
- `2` - **Terrestre** 🌿
- `3` - **Aéreo** ☁️

## 📌 Regras básicas do tabuleiro

- **Duas equipes:** `Ordem` e `Progresso`.
- **Objetivo:** Jogadores começam nas bases e precisam alcançar a base inimiga.
- **Divisão por lanes e jungle:**
  - **Lanes** destacadas nas bordas do tabuleiro.
  - **Jungle** no centro para interações estratégicas.
- **Torres:** Protegem as lanes e estão distribuídas estrategicamente.
- **Monstros neutros:** Localizados na jungle para gerar recursos ou buffs.

## 🎨 Elementos do tabuleiro

| Elemento        | Descrição |
|----------------|-----------|
| 🔳 **Diagonais** | Destacadas para referência visual. |
| 🚩 **Ordem (Base)** | Posição `(10,0)`, destacada em **laranja**. |
| 🚩 **Progresso (Base)** | Posição `(0,10)`, destacada em **verde-limão**. |
| 🏰 **Torres** | Protegem lanes e bases, destacadas em **dourado**. |
| 👹 **Monstros** | Encontrados na jungle, destacadas em **vermelho escuro**. |

---

## 📜 Changelog

### 🆕 **Versão Atual**
- Criado tabuleiro **11x11x3** com camadas visíveis.
- Adicionadas **lanes visuais** (`Top`, `Bottom`, `Left`, `Right`, `Jungle`).
- Implementadas **torres estratégicas** em posições fixas.
- Adicionados **monstros** em células de jungle.
- Melhorado destaque da **diagonal principal** e **diagonal secundária**.
- Melhorada visibilidade do subterrâneo.

---

## 🚀 Como usar

Basta abrir o arquivo HTML no navegador para visualizar o tabuleiro.

---

### 💡 Próximos Passos
- Implementar movimentação dos heróis.
- Adicionar lógica de combate e cartas.
- Criar interações entre monstros, torres e jogadores.
