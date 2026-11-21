# 🧑‍💻 Mini Dev Studio 3D (Dev Idle)

Jogo *arcade idle / tycoon* 3D em formato **PWA** feito com **Three.js**, onde você constrói e automatiza sua própria software house — da Estação Web até a Central das IAs.

🎮 **Jogar agora:** https://arthurrosafontes.github.io/Dev-Idle/

## ✨ Recursos
- **10 estações desbloqueáveis** (Web, Mobile, Games, Backend, Lab de IA, Dados, Segurança, Cloud, Enterprise e Central das IAs).
- **Automação completa**: Central de Estagiários por setor (carregadores, entregadores e baristas) + Centrais de Envio Digital.
- **Gestão da empresa**: visibilidade/marketing, capacidade de impressoras e bandejas por setor, QA, sala de descanso, decorações, pets e upgrades visuais.
- **Metagame**: pedidos VIP, megaprojetos em etapas, eventos aleatórios, missões diárias, conquistas, reputação, Closet do CEO e prestígio (Rodadas de Investimento).

## 📁 Estrutura do Projeto
```text
Dev-Idle/
├── index.html             # Página principal do PWA
├── manifest.json          # Manifesto PWA
├── sw.js                  # Service Worker (cache offline)
├── icon-180.png           # Ícone da Tela de Início (iOS)
├── assets/
│   └── icons/
│       ├── icon-192.png
│       └── icon-512.png
├── css/
│   └── style.css          # Estilos do HUD e modais
└── js/
    ├── game.js            # Engine 3D e lógica do jogo
    └── vendor/
        └── three.module.min.js
```
