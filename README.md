<div align="center">

<img src="https://img.shields.io/badge/Will%20Gym-PRO-FF3D25?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48cmVjdCB3aWR0aD0iMTAwIiBoZWlnaHQ9IjEwMCIgcng9IjIwIiBmaWxsPSIjRkYzRDI1Ii8+PHRleHQgeT0iLjllbSIgZm9udC1zaXplPSI4MCIgeD0iMTAiPvCfj618L3RleHQ+PC9zdmc+" alt="Will Gym">

# 🏋️ Will Gym

**Seu treino, sua evolução.**

Aplicação web progressiva (PWA) de academia — 100% offline, sem backend, sem instalação.  
Registre, analise e compartilhe seus treinos direto do navegador.

[![Versão](https://img.shields.io/badge/versão-28.0-FF3D25?style=flat-square)](https://github.com/Martinswillians/WGym)
[![Licença](https://img.shields.io/badge/licença-MIT-green?style=flat-square)](LICENSE)
[![PWA](https://img.shields.io/badge/PWA-Instalável-4A9FFF?style=flat-square)](https://github.com/Martinswillians/WGym)
[![HTML Only](https://img.shields.io/badge/stack-HTML%20%2F%20CSS%20%2F%20JS-F5A623?style=flat-square)](https://github.com/Martinswillians/WGym)

</div>

---

## 📱 Demo

> Abra o arquivo `wgym_v28.html` em qualquer navegador moderno — funciona 100% offline.  
> Para instalar como app no celular: Chrome → menu ⋮ → **"Adicionar à tela inicial"**.

---

## ✨ Funcionalidades

### 🏠 Dashboard
- Métricas rápidas: treinos na semana, volume total, exercício mais treinado
- Recordes pessoais (1RM estimado) com lista de PRs por exercício
- Atalho para o último treino realizado
- Status de treino em tempo real: **Aguardando Início** / **Treinando** / **Treino Finalizado**

### 🏋️ Modos de Treino
| Modo | Descrição |
|------|-----------|
| **Treino A / B / C** | Grupos musculares pré-definidos (Peito, Costas, Pernas, Ombros…) |
| **Superiores** | Foco em membros superiores |
| **Livre** | Montagem livre — qualquer exercício em qualquer ordem |
| **🤖 Sugerido** | IA interna sugere o treino com base no histórico e descanso muscular |
| **👥 Parceiro** | Modo dupla — registra séries de dois atletas simultaneamente |
| **🏃 Aeróbico / Cardio** | Esteira, bike, elíptico com tempo, velocidade e inclinação |

### 💪 Registro de Exercícios
- Registro de séries com **repetições + carga (kg)**
- Cálculo automático de **1RM estimado** (fórmula de Epley)
- Detecção de **novo recorde pessoal (PR)** com badge e celebração
- Pré-preenchimento automático da **última carga** do exercício (sessões anteriores)
- Timer de descanso entre séries com vibração
- Suporte a exercícios aeróbicos: tempo, velocidade, inclinação, intensidade
- Adição de exercícios customizados por grupo
- Favoritar exercícios com ⭐

### 📊 Histórico
- Agrupamento por dia com resumo: exercícios, volume e tempo de cardio
- Agrupamento por **tipo de treino** dentro do dia (Musculação, Cardio, Livre, Sugerido)
- Indicadores de evolução: 🔥 Aumentou carga / 📉 Caiu performance / ⚖️ Manteve
- Edição inline de séries (repetições e carga)
- Edição de data/hora do exercício
- **Exclusão de exercício individual** com confirmação
- Busca por exercício, grupo ou atleta
- Limpeza total do histórico

### 📤 Compartilhamento
- Compartilhar resumo do **exercício** após concluir (WhatsApp, E-mail, Copiar, Mais)
- Compartilhar **resumo completo do treino do dia** ao encerrar — com lista de exercícios, volume, séries e PRs
- Compartilhamento nativo do sistema (Web Share API) com fallback para clipboard

### 📈 Planos & Gráficos
- Visualização de progresso por exercício ao longo do tempo
- Comparativo de volume e 1RM entre sessões
- Criação e gerenciamento de planos de treino personalizados

### 👤 Múltiplos Usuários & Contas
- Criação de perfis individuais (com avatar emoji e foto)
- Suporte a múltiplos atletas na mesma academia / dispositivo
- Histórico separado por usuário
- Login por conta com sessão persistida

### ⚙️ Configurações
- Tema **Dark** / **Light**
- Vibração nas notificações
- Personalização de grupos musculares
- Gerenciamento de exercícios customizados
- Backup e limpeza de dados

---

## 🛠️ Stack

```
HTML5 · CSS3 · JavaScript (Vanilla)
```

- **Zero dependências** — nenhum framework, nenhuma biblioteca externa
- **Zero backend** — tudo funciona via `localStorage`
- **PWA** — instalável, funciona offline, ícone na tela inicial
- **Single file** — o app inteiro é um único arquivo `.html`

---

## 🚀 Como usar

### Opção 1 — Direto no navegador
```bash
# Clone o repositório
git clone https://github.com/Martinswillians/WGym.git

# Abra o arquivo
open wgym_v28.html   # macOS
start wgym_v28.html  # Windows
xdg-open wgym_v28.html  # Linux
```

### Opção 2 — GitHub Pages
1. Vá em **Settings → Pages**
2. Selecione a branch `main` e raiz `/`
3. Acesse via `https://martinswillians.github.io/WGym/wgym_v28.html`

### Opção 3 — Instalar como app (PWA)
1. Abra no **Chrome** (mobile ou desktop)
2. Menu → **"Adicionar à tela inicial"** / **"Instalar aplicativo"**
3. Use como app nativo — funciona offline

---

## 📁 Estrutura do projeto

```
WGym/
├── wgym_v28.html       # App completo (HTML + CSS + JS em um único arquivo)
├── README.md           # Este arquivo
└── LICENSE             # Licença MIT
```

---

## 🗺️ Histórico de versões

| Versão | Destaques |
|--------|-----------|
| **v28** | Exclusão de exercício com modal de confirmação customizado; fix modal de conclusão de treino |
| **v27** | Fix última carga por exercício individual; modal pós-exercício sem compartilhamento; share ao encerrar treino |
| **v26** | Compartilhar treino do dia; fix updateTrainStatus |
| **v20** | Sistema de status de treino 3 estados; histórico agrupado por tipo de treino |
| **v19** | Base do sistema com múltiplos modos de treino, parceiro, aeróbico e planos |

---

## 🤝 Contribuindo

Pull requests são bem-vindos! Para mudanças maiores, abra uma issue primeiro para discutir o que você gostaria de modificar.

1. Fork o projeto
2. Crie sua branch: `git checkout -b feature/minha-feature`
3. Commit: `git commit -m 'feat: adiciona minha feature'`
4. Push: `git push origin feature/minha-feature`
5. Abra um **Pull Request**

---

## 📄 Licença

Distribuído sob a licença MIT. Veja [`LICENSE`](LICENSE) para mais informações.

---

<div align="center">

Feito com 🔥 por [Willians Martins](https://github.com/Martinswillians)

*"Seu treino, sua evolução."*

</div>
