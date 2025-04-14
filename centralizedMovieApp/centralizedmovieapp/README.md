# 🎬 Central de Conteúdos Audiovisuais

**Ricardo Batista – 79298 – a79298@ualg.pt**  
**Ricardo Vilhena – 79305 – a79305@ualg.pt**

Proposta para o Trabalho Final – LESTI – Computação Móvel

---

## 📌 Resumo

Este projeto propõe o desenvolvimento de uma aplicação móvel desenvolvida com **Flutter**, que centraliza informações sobre **filmes**, **séries**, **documentários** e **programas de televisão**. A app irá buscar dados a fontes como **IMDb**, **TMDB**, **Rotten Tomatoes**, **Letterboxd**, e a plataformas de streaming como **JustWatch**.

O objetivo é fornecer ao utilizador uma ferramenta completa e intuitiva, onde possa consultar sinopses, avaliações, trailers, elenco, e descobrir onde o conteúdo está disponível para visualização. Será ainda possível calcular uma **média de ratings** com base nas diferentes fontes.

---

## 💡 Funcionalidades

### 🔍 Pesquisa inteligente
- Por título, ator, realizador ou género.
- Sugestões automáticas e correção de erros.

### 🎞️ Informações detalhadas
- Sinopse, trailer, ano, duração, elenco, género, realizador.
- Avaliações de múltiplas fontes (IMDb, TMDB, Rotten Tomatoes, Letterboxd).
- Cálculo automático de média de avaliações.

### 📺 Onde assistir
- Indicação das plataformas de streaming disponíveis.
- Filtros por país e por plataforma.

### ⭐ Listas e Favoritos
- Marcar conteúdos como favoritos.
- Criar listas personalizadas (“Ver mais tarde”, “Já visto”, “Recomendar”, etc).

### 📱 Interface moderna e responsiva
- Desenvolvida com **Flutter**.
- Compatível com **Android**, **iOS**, **Web** e **Desktop**.

---

## 🛠️ Tecnologias

- **Flutter (Dart)** — Interface e lógica da aplicação.
- **APIs externas**:
  - [IMDb](https://www.imdb.com), [TMDB](https://www.themoviedb.org), [Rotten Tomatoes](https://www.rottentomatoes.com), [Letterboxd](https://letterboxd.com), [JustWatch](https://www.justwatch.com)
- **SQLite / JSON local** — Armazenamento de dados e listas.
- **OAuth 2.0 com Google** — Autenticação segura.
- **Fernet** — Encriptação local.
- **Replit / Fly.io** — Deployment online.
- **GitHub** — Controlo de versão e colaboração.

---

## 📅 Plano de Desenvolvimento

### Fase 1 – Estrutura Inicial
- Configuração do Flutter e dependências.
- Estrutura de pastas e navegação base.

### Fase 2 – Pesquisa e Apresentação
- Ligação às APIs externas.
- Implementação do motor de pesquisa.
- Visualização detalhada de cada título.

### Fase 3 – Onde Assistir
- Integração com JustWatch (ou alternativa).
- Filtros por país/plataforma.

### Fase 4 – Funcionalidades do Utilizador
- Sistema de favoritos e listas locais.
- Encriptação com Fernet.
- Login com Google OAuth e suporte offline.

### Fase 5 – Finalização e Deploy
- Testes e otimização.
- Exportação e publicação para Web, Android e iOS.

---

## ✅ Estado Atual

📍 Documento de proposta finalizado.  

📍 Começo do desenvolvimento do projeto

---

> Projeto académico desenvolvido no âmbito da unidade curricular de **Computação Móvel** – LESTI – Universidade do Algarve
