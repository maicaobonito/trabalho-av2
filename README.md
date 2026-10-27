<div align="center">

# 🎮 Plataforma 2D em Godot

**Jogo de plataforma 2D feito em Godot 4 com GDScript, inspirado nos clássicos do gênero.**

<img src="https://img.shields.io/badge/Godot%204-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" alt="Godot 4" />
<img src="https://img.shields.io/badge/GDScript-355570?style=for-the-badge&logo=godotengine&logoColor=white" alt="GDScript" />
<img src="https://img.shields.io/badge/Unifor-AV2-5b21b6?style=for-the-badge" alt="Unifor AV2" />

</div>

## O que tem no jogo

- Tela inicial, fase tutorial, fase 1 e tela de encerramento
- Personagem com física de plataforma (corrida, pulo e colisões)
- Inimigos com comportamentos próprios, cada um com seu script
- Lava como obstáculo nas fases
- Sistema de pontuação com contador na tela
- Cenário de caverna com tileset, fundo em camadas e trilha sonora

## Estrutura

```
mario-main/
├── Cenas/       # cenas principais: main, Player, fase tutorial, inimigos, HUD de pontos
├── Scripts/     # lógica do jogador e dos inimigos (GDScript)
├── Resources/   # formas de colisão
├── Assets/      # sprites, tileset, fundos e áudio
├── tela_inicial.tscn / fase_1.tscn / finalizar.tscn
└── project.godot
```

## Como rodar

1. Baixe o `trabalho-godot-av2.zip` deste repositório e extraia
2. Abra o **Godot 4**, clique em **Importar** e selecione o `project.godot` dentro de `mario-main/`
3. Aperte **F5** pra jogar

---

<div align="center"><sub>Projeto da AV2 na Unifor · feito por <a href="https://github.com/maicaobonito">Michael David</a></sub></div>
