# Agamenon

Developed with Unreal Engine 4
Edited on GitHub

Entrega: Exercício Módulo 30

-Adicionado função de pular introdução (Backspace) dentro da Level Blueprint - Landscape;
-Implementado sistema de Save/Load básico:
  - Salva variáveis como vida de personagem, moedas, itens pegos;
  - Salva Posição do personagem;
    > Ao carregar, o personagem aparece na posição salva, desde que não seja necessário mudar de level (não funciona bem no menu principal);
  - Função de salvar os atores destruídos e destruí-los no load ainda em desenvolvimento;

A função de save está disponível no menu de pausa (P ou ESC - Standalone Game) ou por comando do personagem (9)
A função de load está disponível no menu principal, no menu de pausa (P ou ESC - Standalone Game) ou por comando do personagem (0)
