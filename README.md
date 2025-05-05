# Controle de Versão - Projeto Equipe Alpha

Este repositório simula a estrutura de controle de versão adotada pela equipe Alpha, conforme o estudo de caso proposto na HQ2.

## 📚 Objetivo

Implementar boas práticas de versionamento de código utilizando Git, GitHub e versionamento semântico (SemVer), promovendo colaboração e rastreabilidade.

## 🚀 Estratégia de Branches

- `main` → código estável
- `develop` → desenvolvimento em andamento
- `feature/*` → novas funcionalidades
- `hotfix/*` → correções urgentes direto na main
- `release/*` → preparação de novas versões

## ✅ Boas Práticas Implementadas

- **Conventional Commits**: mensagens como `feat:`, `fix:`, `docs:`
- **Pull Requests com revisão obrigatória de 2 membros**
- **CI/CD** com validações automáticas (ex: GitHub Actions)
- **Ambiente de staging** para testes antes do deploy
- **SemVer** para controle de versões (`1.0.0`, `1.1.0`, etc)
- **Arquivos de responsabilidade (`CODEOWNERS`)**
- **Template de PR**

## 🔁 Fluxograma de Versionamento

Veja em [`docs/fluxo-versionamento.png`](https://docs.google.com/document/d/1BYMXpScC3UMhhq8zgbvaA2OcYJ5hrqjCHltAZUxAXJs/edit?tab=t.0)

## 📦 Exemplo de aplicação

Código fictício disponível em `src/exemplo/`

---

## 📌 Versão Atual

**v1.0.0** - Estrutura inicial com boas práticas de versionamento
