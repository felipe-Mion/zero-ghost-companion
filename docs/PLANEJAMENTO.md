# Planejamento — ZERO: Ghost Companion

## Proposta

Desenvolver um jogo 2D no qual o jogador utiliza uma webcam e gestos de mão para interagir com o personagem Zero, inspirado em *O Estranho Mundo de Jack*. O projeto deverá utilizar o MediaPipe para reconhecer gestos.

## Mecânica principal

O jogador faz uma pinça com os dedos para segurar o personagem, arrastá-lo e conduzi-lo até pequenas luzes espalhadas pelo cenário. A coleta das luzes permite concluir o desafio.

## Mecânicas complementares

- **Carinho:** gesto de deslizar o dedo sobre a cabeça do personagem, gerando uma reação de alegria.
- **Cutucão:** toque breve em uma área do personagem, gerando uma reação de surpresa.
- **Chamar Zero:** mão aberta faz o personagem olhar ou se aproximar. *Opcional.*

## Requisitos mínimos propostos (MVP)

1. Detectar uma mão pela webcam usando o MediaPipe.
2. Reconhecer o gesto de pinça.
3. Permitir arrastar o personagem enquanto a pinça estiver ativa.
4. Criar pelo menos uma interação complementar (carinho ou cutucão).
5. Implementar pelo menos um objetivo de jogo, como coletar 5 luzes.
6. Apresentar pontuação e uma mensagem de conclusão.

## Desafios técnicos

- Ajustar o gesto de pinça para diferentes tamanhos de mãos e distâncias da câmera.
- Evitar acionamentos repetidos e falsos positivos.
- Converter as coordenadas da câmera para as coordenadas do jogo.
- Suavizar o movimento do personagem.
- Equilibrar uma estética visual própria com o escopo da entrega acadêmica.

## Roadmap

### Etapa 1 — Proposta e documentação
- [x] Definição do conceito.
- [x] README e organização inicial.

### Etapa 2 — Visão computacional
- [ ] Captura de vídeo.
- [ ] Reconhecimento da mão e interpretação de gestos.

### Etapa 3 — Jogo
- [ ] Personagem e movimentação.
- [ ] Interações e animações.
- [ ] Luzes, colisão e pontuação.

### Etapa 4 — Validação e entrega
- [ ] Testes com webcam.
- [ ] Correções.
- [ ] Vídeo ou GIF demonstrativo.
- [ ] Instruções de instalação e execução.

