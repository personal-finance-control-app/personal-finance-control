# 🚀 Finance Control - Dashboard Principal

![Finance Control](https://img.shields.io/badge/Project-Finance%20Control-blue)
![Microservices](https://img.shields.io/badge/Architecture-Microservices-green)
![Status](https://img.shields.io/badge/Status-Development-yellow)
![Version](https://img.shields.io/badge/Version-1.0.0--alpha-lightgrey)

## 📊 Status Dashboard em Tempo Real

### 🏗️ Microserviços Backend

| Serviço | Repositório | Versão | Coverage | Status | Monitor |
|---------|-------------|--------|----------|--------|---------|
| **User Service** | [fc-user-service](https://github.com/finance-control-app/fc-user-service) | ![Version](https://img.shields.io/badge/Version-1.2.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-88%25-brightgreen) | ![Status](https://img.shields.io/badge/Status-✅_Active-green) | ![Metrics](https://img.shields.io/badge/Metrics-Prometheus-E6522C) |
| **Auth Service** | [fc-auth-service](https://github.com/finance-control-app/fc-auth-service) | ![Version](https://img.shields.io/badge/Version-1.1.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-92%25-brightgreen) | ![Status](https://img.shields.io/badge/Status-✅_Active-green) | ![Metrics](https://img.shields.io/badge/Metrics-Prometheus-E6522C) |
| **Transaction Service** | [fc-transaction-service](https://github.com/finance-control-app/fc-transaction-service) | ![Version](https://img.shields.io/badge/Version-1.3.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-85%25-brightgreen) | ![Status](https://img.shields.io/badge/Status-🟡_Development-yellow) | ![Metrics](https://img.shields.io/badge/Metrics-Prometheus-E6522C) |
| **Report Service** | [fc-report-service](https://github.com/finance-control-app/fc-report-service) | ![Version](https://img.shields.io/badge/Version-0.9.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-78%25-yellow) | ![Status](https://img.shields.io/badge/Status-🔧_WIP-orange) | ![Metrics](https://img.shields.io/badge/Metrics-Prometheus-E6522C) |

### 🌐 Frontend & Gateway

| Componente | Repositório | Versão | Coverage | Status | Deploy |
|------------|-------------|--------|----------|--------|--------|
| **API Gateway** | [fc-api-gateway](https://github.com/finance-control-app/fc-api-gateway) | ![Version](https://img.shields.io/badge/Version-1.0.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-82%25-brightgreen) | ![Status](https://img.shields.io/badge/Status-🟡_Development-yellow) | ![K8s](https://img.shields.io/badge/Deploy-Kubernetes-326CE5) |
| **Frontend Angular** | [fc-frontend](https://github.com/finance-control-app/fc-frontend) | ![Version](https://img.shields.io/badge/Version-2.0.0-blue) | ![Coverage](https://img.shields.io/badge/Coverage-90%25-brightgreen) | ![Status](https://img.shields.io/badge/Status-🟡_Development-yellow) | ![Vercel](https://img.shields.io/badge/Deploy-Vercel-000000) |

### ⚙️ Infraestrutura & Bibliotecas

| Componente | Repositório | Versão | Status | Tipo |
|------------|-------------|--------|--------|------|
| **Infrastructure** | [fc-infrastructure](https://github.com/finance-control-app/fc-infrastructure) | ![Version](https://img.shields.io/badge/Version-1.0.0-blue) | ![Status](https://img.shields.io/badge/Status-✅_Active-green) | ![Type](https://img.shields.io/badge/Type-Infrastructure-grey) |
| **Shared Contracts** | [fc-shared-contracts](https://github.com/finance-control-app/fc-shared-contracts) | ![Version](https://img.shields.io/badge/Version-1.0.0-blue) | ![Status](https://img.shields.io/badge/Status-✅_Active-green) | ![Type](https://img.shields.io/badge/Type-Library-lightblue) |
| **Service Template** | [fc-service-template](https://github.com/finance-control-app/fc-service-template) | ![Version](https://img.shields.io/badge/Version-1.0.0-blue) | ![Status](https://img.shields.io/badge/Status-✅_Active-green) | ![Type](https://img.shields.io/badge/Type-Template-yellow) |

## 📈 Métricas do Sistema

![Uptime](https://img.shields.io/badge/Overall_Uptime-99.95%25-brightgreen)
![Response Time](https://img.shields.io/badge/Avg_Response-45ms-green)
![Requests Day](https://img.shields.io/badge/Daily_Requests-150K-blue)
![Error Rate](https://img.shields.io/badge/Error_Rate-0.02%25-green)

## 🚀 Como Utilizar o Service Template

### 📋 O que é o Service Template?
O **fc-service-template** é um repositório template que contém toda a configuração base para criar novos microserviços de forma padronizada.

### 🏗️ Estrutura do Template:
```
fc-service-template/
├── .github/
│ └── workflows/
│ ├── ci.yml # CI pipeline
│ ├── cd.yml # CD pipeline
│ └── codeql-analysis.yml # Security scanning
├── src/
│ ├── domain/ # Entidades e regras de negócio
│ ├── application/ # Casos de uso
│ ├── infrastructure/ # Implementações concretas
│ ├── main.py # Entry point
│ └── config.py # Configurações
├── tests/
│ ├── unit/ # Testes unitários
│ ├── integration/ # Testes de integração
│ └── conftest.py # Fixtures
├── Dockerfile # Container configuration
├── requirements.txt # Dependencies
├── .dockerignore
├── .gitignore
├── pyproject.toml # Tool configuration
└── README.md # Documentation
```

### 🔧 Como Criar um Novo Microserviço a Partir do Template:

```bash
# 1. Usar o template pelo GitHub UI
# Visite: https://github.com/finance-control-app/fc-service-template
# Clique em "Use this template" → "Create a new repository"

# 2. Ou via GitHub CLI:
gh repo create finance-control-app/fc-NOVO-service \
  --template finance-control-app/fc-service-template \
  --public \
  --add-topic "finance-control" \
  --add-topic "microservice" \
  --add-topic "python"

# 3. Clone o novo repositório
gh repo clone finance-control-app/fc-NOVO-service
cd fc-NOVO-service

# 4. Configure o novo serviço
# Edite src/config.py, atualize as dependências, etc.
```

## 🎯 Resumo do Service Template

### **O que tem no repositório template?**:
- ✅ **Estrutura de pastas** padronizada
- ✅ **CI/CD Pipeline** configurado
- ✅ **Dockerização** pronta
- ✅ **Configurações base** de logging, health checks, metrics
- ✅ **Test framework** configurado
- ✅ **Code quality tools** pré-setup
- ✅ **Documentação** template

### **Como usar**:
1. Criar novo repo from template
2. Personalizar para o serviço específico  
3. Configurar variáveis de ambiente
4. Adicionar dependências específicas
5. Implementar lógica de negócio
