# 🎮 Aethernal Code

<div align="center">
  
![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Pygame](https://img.shields.io/badge/Pygame-2.0+-green?logo=pygame&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-In%20Development-orange)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

**Um MMORPG Open Source construído com Python e Pygame**

*Criando mundos, conectando pessoas, desenvolvendo juntos*

[🚀 Começar](#-instalação) • [📖 Documentação](#-documentação) • [🤝 Contribuir](#-como-contribuir) • [💬 Comunidade](#-contato-e-suporte)

</div>

---

## 📜 Sobre o Projeto

**Aethernal Code** é mais que um jogo - é uma experiência colaborativa de desenvolvimento de um MMORPG completamente **open source**. Nosso objetivo é criar um mundo virtual persistente, rico em narrativas e totalmente moldado pela comunidade.

### 🎯 Nossa Missão
- Desenvolver um MMORPG acessível e educativo
- Fomentar o aprendizado colaborativo de programação
- Criar uma comunidade inclusiva de desenvolvedores e jogadores
- Demonstrar o poder do desenvolvimento open source

## ✨ Características Principais

### 🌍 Mundo do Jogo
- **Mundo Expansivo**: Explore um vasto continente com cidades, masmorras e territórios selvagens
- **Mundo Persistente**: Suas ações têm consequências duradouras no universo do jogo
- **Eventos Dinâmicos**: Sistema de eventos que responde às ações dos jogadores

### ⚔️ Sistema de Gameplay
- **Sistema de Classes**: Guerreiro, Mago, Arqueiro, Ladino e classes híbridas
- **Progressão de Habilidades**: Sistema de níveis e especialização de talentos
- **Combate Estratégico**: Batalhas em tempo real com elementos táticos
- **Sistema de Guilds**: Forme alianças e conquiste territórios

### 🔨 Sistemas Econômicos
- **Crafting Avançado**: Colete recursos e forje equipamentos únicos
- **Economia Dinâmica**: Mercado controlado pelos jogadores
- **Sistema de Trocas**: Comércio seguro entre aventureiros
- **Leilões e Mercados**: Centros comerciais em grandes cidades

### 🎨 Características Técnicas
- **Arquitetura Cliente-Servidor**: Suporte a centenas de jogadores simultâneos
- **Sistema de Chat**: Comunicação global, local e por guild
- **Anti-Cheat**: Validação server-side de todas as ações
- **Save Automático**: Progresso sempre seguro

## 🛠️ Stack Tecnológica

| Componente | Tecnologia | Versão | Descrição |
|------------|------------|--------|-----------|
| **Linguagem** | Python | 3.8+ | Linguagem principal do projeto |
| **Interface Gráfica** | Pygame | 2.0+ | Renderização 2D e interface |
| **Networking** | Twisted/AsyncIO | Latest | Servidor assíncrono |
| **Base de Dados** | SQLite/PostgreSQL | - | Persistência de dados |
| **Serialização** | Pickle/JSON | - | Comunicação cliente-servidor |

## 🚀 Instalação

### Pré-requisitos
- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)
- Git

### 🚀 Instalação Rápida

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/aethernal-code.git
cd aethernal-code

# Crie um ambiente virtual (recomendado)
python -m venv venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate     # Windows

# Instale as dependências
pip install -r requirements.txt

# Execute o cliente (conecta automaticamente ao servidor oficial)
python client.py
```

### 🌐 Servidor Oficial vs Desenvolvimento Local

#### 🎮 **Modo Jogador (Recomendado)**
```bash
# Conecta ao servidor oficial - sem configuração adicional
python client.py
# Servidor: aethernal-code.ddns.net:7777
```

#### 🛠️ **Modo Desenvolvedor (Contribuidores)**
```bash
# Para desenvolvimento e testes locais
cd server/
python server.py

# Em outro terminal, execute o cliente local
cd client/
python client.py --local
```

> ⚠️ **Nota**: Servidores privados requerem autorização. Ver [Licença e Uso](#️-licença-e-uso)

## 🎮 Como Jogar

### 🌐 **Conectar ao Servidor Oficial**
1. **Download**: Clone o repositório ou baixe o release
2. **Primeira Vez**: Crie sua conta e personalize seu personagem
3. **Conectar**: O cliente conecta automaticamente ao servidor oficial
4. **Explorar**: Use WASD para mover, mouse para interagir
5. **Socializar**: Use o chat para conversar com outros jogadores online

### 🎯 **Servidor Oficial vs Local**
- **🌐 Oficial**: Jogadores reais, economia ativa, eventos especiais
- **🏠 Local**: Apenas para desenvolvimento (requer autorização para servidor privado)

### Controles Básicos
- `WASD` - Movimento
- `Mouse` - Interação e combate
- `I` - Inventário
- `C` - Painel de personagem
- `Enter` - Chat
- `M` - Mapa

## 📖 Documentação

- [📘 Guia do Desenvolvedor](docs/developer-guide.md)
- [🎯 Roadmap do Projeto](docs/roadmap.md)
- [🏗️ Arquitetura do Sistema](docs/architecture.md)
- [🎨 Guia de Arte e Assets](docs/art-guide.md)
- [🐛 Como Reportar Bugs](docs/bug-reports.md)

## 🤝 Como Contribuir

Adoramos receber contribuições! Existem várias formas de ajudar:

### 💻 Desenvolvimento
- **Backend**: Sistema de servidor, database, APIs
- **Frontend**: Interface do usuário, gameplay
- **Networking**: Otimização de rede, anti-cheat
- **Ferramentas**: Editores de mapa, ferramentas de desenvolvimento

### 🎨 Arte e Design
- **Sprites**: Personagens, NPCs, inimigos
- **Ambientes**: Tilesets, backgrounds, mapas
- **Interface**: Menus, HUD, iconografia
- **Som**: Música, efeitos sonoros

### 📝 Conteúdo
- **Narrativa**: Quests, diálogos, lore do mundo
- **Balanceamento**: Sistema de combate, economia
- **Documentação**: Guias, tutoriais, API docs
- **Tradução**: Localização para outros idiomas

### 🧪 Testes e QA
- **Bug Hunting**: Encontre e reporte problemas
- **Playtesting**: Teste gameplay e balance
- **Performance**: Otimização e profiling
- **Usabilidade**: Experiência do usuário

### Processo de Contribuição

1. **Fork** o projeto
2. **Crie uma branch** para sua feature (`git checkout -b feature/nova-feature`)
3. **Commite** suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. **Push** para a branch (`git push origin feature/nova-feature`)
5. **Abra um Pull Request**

## 📊 Status do Desenvolvimento

### ✅ Concluído
- [x] Estrutura básica do projeto
- [x] Sistema de movimento do jogador
- [x] Renderização de mapas básica
- [x] Sistema de colisão
- [x] Interface de usuário básica

### 🔄 Em Desenvolvimento
- [ ] Sistema de combate (80%)
- [ ] Servidor multiplayer (60%)
- [ ] Sistema de inventário (70%)
- [ ] Sistema de chat (40%)
- [ ] Editor de mapas (30%)

### 📋 Próximos Passos
- [ ] Sistema de guilds
- [ ] PvP balanceado
- [ ] Sistema de quests dinâmico
- [ ] Marketplace de itens
- [ ] Sistema de casas/propriedades

## 👥 Equipe Principal

| Avatar | Nome | Papel | GitHub |
|--------|------|-------|---------|
| 🎯 | **Você** | Project Lead & Backend Developer | [@seu-usuario](https://github.com/seu-usuario) |
| 🎨 | **Contribuidor** | Art Director | *Procurando* |
| 🔊 | **Contribuidor** | Sound Designer | *Procurando* |
| 📖 | **Contribuidor** | Narrative Designer | *Procurando* |

*Interessado em se juntar à equipe principal? Entre em contato!*

## 📈 Estatísticas

```
🔢 Linhas de Código: ~5.000+
📁 Arquivos: 50+
🧪 Testes: 25+
📝 Commits: 100+
👥 Contribuidores: 3
⭐ Stars: Seja o primeiro!
```

## 🌟 Reconhecimentos

Agradecimentos especiais a:
- **Pygame Community** - Pela excelente biblioteca e documentação
- **Python Software Foundation** - Por tornar Python incrível
- **Open Source Community** - Por inspirar este projeto
- **Nossos Contribuidores** - Vocês tornam este projeto possível



## 🔗 Links Importantes

- **🌐 Website**: [Em breve]
- **🎮 Servidor Oficial**: `aethernal-code.ddns.net:7777` 🟢 **ONLINE**
- **📊 Status do Servidor**: [Monitor em tempo real](http://aethernal-code.ddns.net:8080/status)
- **📋 Kanban Board**: [Link do Trello/GitHub Projects]
- **🎮 Downloads**: [Releases](https://github.com/seu-usuario/aethernal-code/releases)
- **⚖️ Termos de Uso**: [Leia nossa política](#️-licença-e-uso)

## 💬 Contato e Suporte

### 📬 Canais Oficiais
- **📧 Email**: suporte.megaflixx@gmail.com
- **💬 WhatsApp**: +55 17 99124-1305
- **🐛 Bug Reports**: [Issues](https://github.com/seu-usuario/aethernal-code/issues)
- **💡 Sugestões**: [Discussions](https://github.com/seu-usuario/aethernal-code/discussions)

### 🌐 Redes Sociais
- **Discord**: [Em breve] - Chat em tempo real
- **Reddit**: r/AethernalCode - Comunidade de jogadores
- **Twitter**: @AethernalCode - Novidades e updates

---

<div align="center">

### ⭐ **Se você gostou do projeto, deixe uma estrela!** ⭐

### 🎮 **JOGUE AGORA: `aethernal-code.ddns.net:7777`** 🎮

### 🚀 **Junte-se à nossa jornada de criar o próximo grande MMORPG open source!** 🚀

---

**⚖️ Respeite nossos [Termos de Uso](#️-licença-e-uso) | 🤝 Contribuições sempre bem-vindas | 💬 Dúvidas? Entre em contato**

*Feito com ❤️ pela comunidade Aethernal Code*

</div>
