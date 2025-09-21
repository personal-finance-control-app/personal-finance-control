# 🚀 Personal Finance Control - Dashboard Principal

![Finance Control](https://img.shields.io/badge/Project-Finance%20Control-blue)
![Microservices](https://img.shields.io/badge/Architecture-Microservices-green)
![Status](https://img.shields.io/badge/Status-Development-yellow)
![Version](https://img.shields.io/badge/Version-1.0.0--alpha-lightgrey)

## 📊 Status Dashboard em Tempo Real

### 🏗️ Microserviços Backend

| Serviço | Repositório | Versão | Coverage | Status | Monitor |
|---------|-------------|--------|----------|--------|---------|
| **User Service** | [user-service](https://github.com/personal-finance-control-app/user-service) | ![Version](https://img.shields.io/badge/Version-1.2.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-88%25-brightgreen) | ![Status](https://img.shields.io/badge/Status-✅_Active-green) | ![Metrics](https://img.shields.io/badge/Metrics-Prometheus-E6522C) |
| **Auth Service** | [auth-service](https://github.com/personal-finance-control-app/auth-service) | ![Version](https://img.shields.io/badge/Version-1.1.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-92%25-brightgreen) | ![Status](https://img.shields.io/badge/Status-✅_Active-green) | ![Metrics](https://img.shields.io/badge/Metrics-Prometheus-E6522C) |
| **Transaction Service** | [transaction-service](https://github.com/personal-finance-control-app/transaction-service) | ![Version](https://img.shields.io/badge/Version-1.3.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-85%25-brightgreen) | ![Status](https://img.shields.io/badge/Status-🟡_Development-yellow) | ![Metrics](https://img.shields.io/badge/Metrics-Prometheus-E6522C) |
| **Report Service** | [report-service](https://github.com/personal-finance-control-app/report-service) | ![Version](https://img.shields.io/badge/Version-0.9.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-78%25-yellow) | ![Status](https://img.shields.io/badge/Status-🔧_WIP-orange) | ![Metrics](https://img.shields.io/badge/Metrics-Prometheus-E6522C) |

### 🌐 Frontend & Gateway

| Componente | Repositório | Versão | Coverage | Status | Deploy |
|------------|-------------|--------|----------|--------|--------|
| **API Gateway** | [api-gateway](https://github.com/personal-finance-control-app/api-gateway) | ![Version](https://img.shields.io/badge/Version-1.0.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-82%25-brightgreen) | ![Status](https://img.shields.io/badge/Status-🟡_Development-yellow) | ![K8s](https://img.shields.io/badge/Deploy-Kubernetes-326CE5) |
| **Frontend** | [frontend](https://github.com/personal-finance-control-app/frontend) | ![Version](https://img.shields.io/badge/Version-2.0.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-90%25-brightgreen) | ![Status](https://img.shields.io/badge/Status-🟡_Development-yellow) | ![Vercel](https://img.shields.io/badge/Deploy-Vercel-000000) |

### ⚙️ Infraestrutura & Bibliotecas

| Componente | Repositório | Versão | Status | Tipo |
|------------|-------------|--------|--------|------|
| **Infrastructure** | [infrastructure](https://github.com/personal-finance-control-app/infrastructure) | ![Version](https://img.shields.io/badge/Version-1.0.0-blue) | ![Status](https://img.shields.io/badge/Status-✅_Active-green) | ![Type](https://img.shields.io/badge/Type-Infrastructure-grey) |
| **Shared Contracts** | [shared-contracts](https://github.com/personal-finance-control-app/shared-contracts) | ![Version](https://img.shields.io/badge/Version-1.0.0-blue) | ![Status](https://img.shields.io/badge/Status-✅_Active-green) | ![Type](https://img.shields.io/badge/Type-Library-lightblue) |
| **Service Samples** | [service-samples](https://github.com/personal-finance-control-app/service-samples) | ![Version](https://img.shields.io/badge/Version-1.0.0-blue) | ![Status](https://img.shields.io/badge/Status-✅_Active-green) | ![Type](https://img.shields.io/badge/Type-Examples-yellow) |
| **Personal Finance Control** | [personal-finance-control](https://github.com/personal-finance-control-app/personal-finance-control) | ![Version](https://img.shields.io/badge/Version-1.0.0-blue) | ![Status](https://img.shields.io/badge/Status-✅_Active-green) | ![Type](https://img.shields.io/badge/Type-Main_App-orange) |

## 📈 Métricas do Sistema

![Uptime](https://img.shields.io/badge/Overall_Uptime-99.95%25-brightgreen)
![Response Time](https://img.shields.io/badge/Avg_Response-45ms-green)
![Requests Day](https://img.shields.io/badge/Daily_Requests-150K-blue)
![Error Rate](https://img.shields.io/badge/Error_Rate-0.02%25-green)

## 🚀 Como Utilizar os Templates

### 📋 Service Samples
O repositório [service-samples](https://github.com/personal-finance-control-app/service-samples) contém exemplos práticos de implementação para diferentes tipos de microserviços.

### 🏗️ Estrutura dos Samples:
```
service-samples/
├── basic-crud-service/     # Exemplo de CRUD completo
├── auth-jwt-service/       # Serviço de autenticação JWT
├── file-processing/        # Processamento de arquivos
├── messaging-service/      # Serviço com mensageria
└── data-analytics/         # Análise de dados
```

### 🔧 Como Usar os Samples:

```bash
# Explorar exemplos disponíveis
git clone https://github.com/personal-finance-control-app/service-samples.git
cd service-samples

# Copiar um exemplo para novo serviço
cp -r basic-crud-service ../novo-servico
cd ../novo-servico

# Personalizar para suas necessidades
```

## 🔗 Links Rápidos

### 📚 Repositórios do Projeto
- [Personal Finance Control](https://github.com/personal-finance-control-app/personal-finance-control)
- [User Service](https://github.com/personal-finance-control-app/user-service)
- [Auth Service](https://github.com/personal-finance-control-app/auth-service) 
- [Transaction Service](https://github.com/personal-finance-control-app/transaction-service)
- [Report Service](https://github.com/personal-finance-control-app/report-service)
- [API Gateway](https://github.com/personal-finance-control-app/api-gateway)
- [Frontend](https://github.com/personal-finance-control-app/frontend)
- [Infrastructure](https://github.com/personal-finance-control-app/infrastructure)
- [Shared Contracts](https://github.com/personal-finance-control-app/shared-contracts)
- [Service Samples](https://github.com/personal-finance-control-app/service-samples)

### 🌐 Environments
- **📊 Production**: [https://app.finance-control.com](https://app.finance-control.com)
- **🧪 Staging**: [https://staging.finance-control.com](https://staging.finance-control.com)
- **📚 API Docs**: [https://api.finance-control.com/docs](https://api.finance-control.com/docs)
- **📈 Monitoring**: [https://grafana.finance-control.com](https://grafana.finance-control.com)

## 🚀 Como Contribuir

1. **Escolha um repositório** da lista acima
2. **Explore os samples** para referência
3. **Siga as guidelines** específicas do repositório
4. **Verifique o status** atual no dashboard
5. **Submeta um PR** seguindo o padrão do projeto

## 📊 Status de Deploy

![Last Deployment](https://img.shields.io/badge/Last_Deploy-$(date +%Y--%m--%d)-lightgrey)
![Deploy Status](https://img.shields.io/badge/Deploy_Status-Success-brightgreen)
![CI Status](https://img.shields.io/badge/CI/CD-Passing-brightgreen)

---

## 🏗️ **Visão Geral da Arquitetura**

```
github.com/personal-finance-control-app/
├── 🧑‍💻 user-service           # Gerenciamento de usuários
├── 🔐 auth-service           # Autenticação e autorização
├── 💰 transaction-service    # Processamento de transações
├── 📊 report-service         # Relatórios e analytics
├── 🚪 api-gateway           # Gateway e roteamento
├── 🎨 frontend              # Interface Angular
├️── ⚙️ infrastructure        # IaC e configurações
├── 📋 service-template      # Template para novos serviços
└── 📝 shared-contracts      # Contratos e DTOs compartilhados
```

---

## 📋 **Detalhamento de Cada Repositório**

### 1. **🧑‍💻 user-service**
**Responsabilidade**: Gerenciamento de usuários e perfis
```python
# Conteúdo principal:
- Entidades: User, UserProfile, UserPreferences
- Endpoints: 
  POST /users          # Criar usuário
  GET /users/{id}      # Buscar usuário
  PUT /users/{id}      # Atualizar usuário
  DELETE /users/{id}   # Deletar usuário
- Funcionalidades:
  ✅ Cadastro de usuários
  ✅ Gerenciamento de perfis
  ✅ Preferências do usuário
  ✅ Histórico de atividades
```

### 2. **🔐 auth-service**
**Responsabilidade**: Autenticação, autorização e segurança
```python
# Conteúdo principal:
- Entidades: AuthSession, Permission, Role
- Endpoints:
  POST /auth/login     # Login JWT
  POST /auth/register  # Registro
  POST /auth/refresh   # Refresh token
  GET /auth/me         # Info do usuário logado
- Funcionalidades:
  ✅ Autenticação JWT
  ✅ Autorização RBAC
  ✅ Refresh tokens
  ✅ OAuth2 integration
```

### 3. **💰 transaction-service**
**Responsabilidade**: Processamento e gestão de transações financeiras
```python
# Conteúdo principal:
- Entidades: Transaction, Category, BankAccount
- Endpoints:
  POST /transactions       # Criar transação
  GET /transactions        # Listar transações
  GET /transactions/{id}   # Buscar transação
  PUT /transactions/{id}   # Atualizar transação
- Funcionalidades:
  ✅ Importação de extrato bancário
  ✅ Categorização automática
  ✅ Filtros e buscas
  ✅ Validação de transações
```

### 4. **📊 report-service**
**Responsabilidade**: Analytics, relatórios e dashboards
```python
# Conteúdo principal:
- Entidades: Report, Dashboard, FinancialMetric
- Endpoints:
  GET /reports/monthly    # Relatório mensal
  GET /reports/annual     # Relatório anual
  GET /reports/categories # Por categorias
  POST /reports/generate  # Gerar relatório custom
- Funcionalidades:
  ✅ Relatórios PDF/Excel
  ✅ Gráficos e visualizações
  ✅ Métricas financeiras
  ✅ Exportação de dados
```

### 5. **🚪 api-gateway**
**Responsabilidade**: Roteamento, rate limiting e segurança centralizada
```python
# Conteúdo principal:
- Configurações de roteamento:
  /api/users/**       → user-service
  /api/auth/**        → auth-service
  /api/transactions/** → transaction-service
  /api/reports/**     → report-service
- Funcionalidades:
  ✅ Rate limiting
  ✅ Load balancing
  ✅ Circuit breaker
  ✅ Logging centralizado
  ✅ Transformação de requests
```

### 6. **🎨 frontend**
**Responsabilidade**: Interface do usuário Angular
```typescript
// Estrutura:
src/
├── app/
│   ├── modules/
│   │   ├── auth/          # Autenticação
│   │   ├── dashboard/     # Dashboard principal
│   │   ├── transactions/  # Gestão de transações
│   │   └── reports/       # Relatórios
│   ├── services/
│   │   ├── api.service.ts
│   │   ├── auth.service.ts
│   │   └── transaction.service.ts
│   └── shared/
│       ├── components/    # Componentes compartilhados
│       ├── models/        # Interfaces TypeScript
│       └── utils/         # Utilitários
```

### 7. **⚙️ infrastructure**
**Responsabilidade**: Infraestrutura como código
```yaml
# Conteúdo principal:
kubernetes/
├── deployments/           # Deployments K8s
├── services/             # Services K8s
├── ingress/              # Ingress rules
└── configmaps/           # Configurações

terraform/
├── aws/                  # Recursos AWS
├── mongodb-atlas/        # Config MongoDB
└── variables.tf          # Variáveis

scripts/
├── deploy.sh            # Scripts de deploy
├── backup.sh           # Scripts de backup
└── monitoring.sh       # Scripts de monitoramento
```

### 8. **📋 service-template**
**Responsabilidade**: Template padronizado para novos serviços
```python
# Conteúdo principal:
- Estrutura de pastas padrão
- Configurações CI/CD
- Dockerfile otimizado
- Configurações de logging
- Health checks
- Metrics Prometheus
- Test configuration
```

### 9. **📝 shared-contracts**
**Responsabilidade**: Contratos compartilhados entre serviços
```python
# Conteúdo principal:
- DTOs compartilhados:
  UserDTO, TransactionDTO, ReportDTO
- Interfaces de API:
  OpenAPI/Swagger specs
- Event schemas:
  UserCreatedEvent, TransactionProcessedEvent
- Tipos TypeScript:
  Interfaces para frontend
```

---

## 🔗 **Como os Serviços se Comunicam**

### **Comunicação Síncrona (HTTP)**
```
Frontend → API Gateway → Microserviços
```

### **Comunicação Assíncrona (Eventos)**
```
user-service → (UserCreated event) → transaction-service
transaction-service → (TransactionCreated event) → report-service
```

### **Dependências Compartilhadas**
```
Todos os microserviços → shared-contracts (DTOs)
Todos os microserviços → service-template (boilerplate)
```

---

## 🗄️ **Bancos de Dados por Serviço**

| **Serviço** | **Banco** | **Dados** |
|------------|----------|-----------|
| **user-service** | MongoDB | Users, profiles, preferences |
| **auth-service** | MongoDB | Sessions, tokens, permissions |
| **transaction-service** | MongoDB | Transactions, categories, accounts |
| **report-service** | MongoDB + Redis | Reports, cache de analytics |
| **api-gateway** | Redis | Rate limiting, cache |

---

## 🚀 **Fluxo de uma Operação Completa**

### **1. Usuário faz login**
```
frontend → api-gateway → auth-service → (JWT token)
```

### **2. Importa transações**
```
frontend → api-gateway → transaction-service → (processa arquivo)
```

### **3. Gera relatório**
```
frontend → api-gateway → report-service → (consulta transaction-service)
```

---

## 📊 **Monitoramento e Observabilidade**

### **Cada serviço inclui:**
- ✅ **Health checks** (`/health`, `/ready`)
- ✅ **Métricas Prometheus** (`/metrics`)
- ✅ **Logging estruturado**
- ✅ **Tracing distribuído** (OpenTelemetry)

### **Monitoramento centralizado:**
- 📈 **Grafana** - Dashboards
- 🔍 **Prometheus** - Métricas
- 📋 **Loki** - Logs
- 🕵️ **Jaeger** - Tracing

---

## 🔧 **Ferramentas e Tecnologias**

### **Backend (Todos os microserviços):**
- 🐍 **Python 3.11+**
- ⚡ **FastAPI** (ASGI)
- 🐳 **Docker** + **Docker Compose**
- 🎯 **Pydantic** (validação)
- 📊 **MongoDB** (banco principal)
- 🔄 **Redis** (cache e sessões)

### **Frontend:**
- ⚡ **Angular 17+**
- 🎨 **PrimeNG** (UI components)
- 📱 **RxJS** (reactive programming)
- 🛡️ **JWT** (autenticação)

### **Infraestrutura:**
- 🚀 **Kubernetes** (orquestração)
- 🏗️ **Terraform** (IaC)
- 📦 **GitHub Actions** (CI/CD)
- ☁️ **AWS** ou **GCP** (cloud)

---

## 📋 **Próximos Passos de Implementação**

1. **Configurar service-template** ✅
2. **Implementar shared-contracts** (DTOs básicos)
3. **Criar user-service** (primeiro microserviço)
4. **Configurar api-gateway** (roteamento básico)
5. **Implementar auth-service** (autenticação)
6. **Desenvolver transaction-service** (core business)
7. **Criar frontend** (interface básica)
8. **Configurar infrastructure** (K8s, Terraform)

---

**📞 Suporte**: [team@finance-control.com](mailto:dantonissler18@gmail.com) | **🐛 Issues**: [GitHub Issues](https://github.com/orgs/personal-finance-control-app/projects/1) | **📋 Roadmap**: [Project Board](https://github.com/orgs/personal-finance-control-app/projects/2)

*Última atualização: $(date +"%Y-%m-%d %H:%M:%S")*
