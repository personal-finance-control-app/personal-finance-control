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

**📞 Suporte**: [team@finance-control.com](mailto:dantonissler18@gmail.com) | **🐛 Issues**: [GitHub Issues](https://github.com/orgs/personal-finance-control-app/projects/1) | **📋 Roadmap**: [Project Board](https://github.com/orgs/personal-finance-control-app/projects/2)

*Última atualização: $(date +"%Y-%m-%d %H:%M:%S")*
