# 🗳️ Urna Cidadã 2026 — Simulador & Pesquisa Eleitoral

> **Simulador interativo de urna eletrônica com apuração em tempo real integrada via Firebase Realtime Database.**

---

## 📌 Sobre o Projeto

O **Urna Cidadã 2026** é uma aplicação web responsiva criada para simular a experiência de votação da urna eletrônica brasileira. O projeto realiza um levantamento independente de intenção de voto com contagem global automatizada e sincronizada na nuvem.

### 🔗 Acesse a demonstração ativa:
👉 **[shre.ink/urnacidada](https://shre.ink/urnacidada)**  
*(Hospedado no GitHub Pages: `https://cermotta.github.io/urna-cidada-2026/`)*

---

## ✨ Principais Funcionalidades

- 📍 **Seleção de Estado (UF):** Obrigatoriedade de escolha do estado antes do registro do voto.
- 🔊 **Efeitos Sonoros Oficiais:** Som das teclas e o bipe longo multitonal ("Pirililililili") gerados via **Web Audio API**.
- 🖼️ **Exibição Dinâmica dos Candidatos:** Fotos com proporção ajustada (`object-fit: cover`) e tags com políticas de segurança contra bloqueio de imagem (`referrerpolicy`).
- ⚡ **Apuração Global em Tempo Real:** Sincronização dos votos de todos os visitantes utilizando o **Firebase Realtime Database**.
- 🔒 **Limite de Voto Único:** Proteção local via `localStorage` para impedir múltiplos votos no mesmo dispositivo.
- 🎨 **Interface Moderna:** Design responsivo em Dark Mode com feedback visual imediato e barras dinâmicas de porcentagem.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3:** Layout moderno estilizado em tema escuro com flexbox e grid.
- **JavaScript (ES6+):** Lógica da urna, controle de eventos e síntese de áudio nativa.
- **Firebase Realtime Database (v10):** Sincronização e transações atômicas de dados na nuvem.
- **GitHub Pages:** Hospedagem estática contínua do projeto.

---

## 🚀 Como Executar ou Rodar Localmente

1. Clone este repositório:
   ```bash
   git clone [https://github.com/cermotta/urna-cidada-2026.git](https://github.com/cermotta/urna-cidada-2026.git)
