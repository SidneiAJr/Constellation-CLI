# 📝 Changelog - Constellation CLI

Todas as mudanças notáveis neste projeto serão documentadas aqui.

---

## [0.1] - Alpha - 2024

### 🎉 Primeira Versão

**Lançamento inicial da Constellation CLI**

---

### ✨ Funcionalidades Implementadas

#### Backends Suportados:
- ✅ **Node.js (JavaScript)** - Express + TypeORM
- ✅ **Node.js (TypeScript)** - Express + TypeORM com tipagem
- ✅ **PHP** - PHP Nativo com estrutura MVC

#### Frontends Suportados:
- ✅ **Angular** - Projeto completo com Angular CLI
- ✅ **React** - Vite + TypeScript
- ✅ **Vanilla** - HTML/CSS/JS com 6 páginas (Home, Login, Register, About, Products, Contact)

#### Mobile:
- ✅ **React Native** - Estrutura Expo pronta

#### Estruturas Criadas:
- ✅ Backend com pastas: controller, model, service, repository, middleware, entity, dto, config, helpers, utils, routes
- ✅ Frontend Angular com CLI oficial
- ✅ Frontend React com Vite
- ✅ Frontend Vanilla com assets (CSS/JS)
- ✅ Documentação básica (README, LICENSE, CONTRIBUTING, routes)

#### Funcionalidades do Script:
- ✅ Menu interativo (MVC ou Vanilla)
- ✅ Submenus para escolha de stack
- ✅ Criação automática de arquivos vazios
- ✅ Geração de JSON de teste (`test.json`)
- ✅ Geração de SQL de teste (`test.sql`)
- ✅ Estrutura de pastas profissional

#### Arquivos Gerados:
- ✅ `server.js` (Node.js com rotas exemplo)
- ✅ `tsconfig.json` (TypeScript)
- ✅ `.env` e `.gitignore`
- ✅ `functions.js` (funções de exemplo)

---

## [1.0] - Beta - 2024/2025

### 🎉 Primeira Versão Estável (Beta)

**Evolução da versão Alpha para Beta estável**

---

### ✨ Novidades em Relação à Versão 0.1

#### Novas Funcionalidades:
- ✅ **Arquivo `.env`** - Configuração de ambiente automática
- ✅ **Docker e Docker Compose** - Containerização pronta
- ✅ **Instalação Automática de Dependências** - npm install automático
- ✅ **Nova Opção no Menu** - Opção 5 (Backend TS + React + Docker)

#### Melhorias:
- 🔧 **create_env()** - Função para criar `.env` automaticamente
- 🔧 **create_env_docker_archives()** - Configurações Docker
- 🔧 **create_docker_files()** - Geração de `docker-compose.yml`
- 🔧 **install_dependencies_1()** - Instala dependências do backend
- 🔧 **install_dependencies_2()** - Instala dependências com Prisma

---

### 📦 Backends Suportados (mantidos)

| Linguagem | Framework | Status |
|-----------|-----------|--------|
| **Node.js** | Express + TypeORM | ✅ JavaScript |
| **Node.js** | Express + TypeORM | ✅ TypeScript |
| **PHP** | PHP Nativo | ✅ MVC estruturado |

---

### 🎨 Frontends Suportados (mantidos)

| Framework | Tecnologia | Status |
|-----------|------------|--------|
| **React** | Vite + TypeScript | ✅ Pronto |
| **Angular** | Angular CLI | ✅ Pronto |
| **Vanilla** | HTML/CSS/JS | ✅ 6 páginas prontas |

---

### 🐳 Docker Suporte (NOVO!)

**Arquivos gerados:**
- `docker-compose.yml` - Container MySQL + Backend
- `.env.docker` - Configurações do ambiente Docker

**Serviços:**
- ✅ Backend Node.js (porta 3000)
- ✅ MySQL 8.0 (porta 3306)
- ✅ Volumes persistentes

---

## [2.0] - Beta Avançado - 2025

### 🎉 Evolução da Versão 1.0

**Grande salto de qualidade e funcionalidades!**

---

### ✨ Novidades em Relação à Versão 1.0

#### 🆕 Novas Funcionalidades:

| Funcionalidade | Descrição | Versão Anterior |
|----------------|-----------|-----------------|
| **Testes Unitários** | Jest + TypeScript para testes | ❌ Não existia |
| **Módulo de Soma** | Testes matemáticos (`soma.test.ts`) | ❌ Não existia |
| **Validação de Usuário** | Testes de validação (`validarUsuario.test.ts`) | ❌ Não existia |
| **Validação de Senha** | Testes de senha forte (`validarSenha.test.ts`) | ❌ Não existia |
| **Pasta Tests** | `Tests/tests/` com estrutura pronta | ❌ Não existia |
| **Nova Opção 6** | Backend JS + Módulos Prontos + React | ❌ Não existia |
| **Arquivos com Código** | Controllers, Services, Models com lógica real | ❌ Só arquivos vazios |

---

### 📦 Novos Arquivos com Código Pronto:

- ✅ `novo_arquivos_backend1` → `.env` configurável
- ✅ `novos_arquivos_backend2` → `database.js` + `env-config.js`
- ✅ `novo_arquivos_backend3` → `user-controller.js` (CRUD completo)
- ✅ `novo_arquivo_backend4` → Middlewares (Auth, Error Handle)
- ✅ `novo_arquivos_backend5` → `user-service.js` (lógica de negócio)
- ✅ `novo_arquivos_backend6` → Models (Usuario, Produto, Pedido, Auth)

---

### 🧪 Testes Implementados:

```typescript
// soma.test.ts
- Subtração de números
- Multiplicação
- Divisão
- Verificação de par/ímpar

// validarUsuario.test.ts
- Validação de nome
- Validação de idade
- Usuário maior/menor de idade

// validarSenha.test.ts
- Senha com 8+ caracteres
- Senha com números
- Casos extremos
```

## 🔧 Opção 6 - Backend JS + Módulos Preencher + React

O que gera:
- Backend com código funcional (CRUD, JWT, validações)
- Frontend React com Vite
- Docker configurado
- Testes unitários

Arquivos gerados com código:
- user-controller.js (CRUD completo)
- user-service.js (lógica de negócio)
- database.js (conexão MySQL)
- auth.middleware.js (JWT)
- Models (Usuario, Produto, Pedido, Auth)

---

## [3.5J] - 2026-05-17
🎉 Versão Enterprise - Java/Spring Boot

### A maior evolução do Constellation CLI!
- ✨ Novidades em Relação à Versão 2.0
- 🆕 Novo Backend:
- ✅ Java/Spring Boot 3.2 - Backend enterprise completo
- ✅ Pom.xml com dependências para nuvem (Azure, Oracle)
- ✅ Application.properties pré-configurado
- ✅ 30+ arquivos Java estruturados
- ✅ Suporte a MySQL, PostgreSQL e Oracle

### 🔧 Melhorias:
- 🔧 Menu interativo aprimorado
- 🔧 Documentação do projeto atualizada
- 🔧 Suporte a múltiplos bancos de dados
  
### 🐛 Corrigido
- Estrutura de pastas do Spring Boot
- Caminho correto do pom.xml
- Application.properties no local certo
- Erros de sintaxe no Bash
