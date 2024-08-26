# Curso-Udemy

# Projeto de um Tabuleiro de Xadrez em C# 👨‍💻

Este é um projeto de xadrez desenvolvido exclusivamente em C#, focado no back-end. O objetivo deste projeto é criar a lógica completa de um jogo de xadrez, incluindo movimentação de peças, verificação de xeque/xeque-mate e outras regras do jogo.

## Funcionalidades 🎯

- Movimento das peças de acordo com as regras do xadrez
- Verificação de xeque e xeque-mate
- Validação de movimentos ilegais
- Registro do histórico de jogadas
- Controle de turno (brancas e pretas)

## Tecnologias Utilizadas 💻

- **Linguagem**: C#
- **Framework**: .NET Core (ou outro, se aplicável)
- **Paradigma**: Programação Orientada a Objetos

## Estrutura do Projeto 📃

O projeto segue uma estrutura modular, com classes separadas para cada peça do jogo, lógica de movimento, tabuleiro, e regras de jogo:

- `Tabuleiro`: Representa o tabuleiro e gerencia as posições das peças.
- `Pecas`: Classes específicas para cada tipo de peça (Rei, Rainha, Torre, Bispo, Cavalo e Peão).
- `RegrasDeJogo`: Contém a lógica para validar os movimentos e determinar o estado do jogo (como xeque/xeque-mate).
