# 🗺️ MLOps Roadmap 2026 - Detalhamento das Fases

Este documento detalha o planejamento estratégico para a transição de carreira para Engenharia de MLOps, utilizando a infraestrutura local (Acer Predator RTX 4070) e focando em certificações da CNCF.

---

## 📅 Fase 1: Fundação & Cloud Native (Jan - Abr)
*O foco é construir a base lógica e o vocabulário técnico.*

### 🐍 Python (Bootcamp Angela Yu)
- **Foco MLOps:** Dias 1-15 (Lógica), Dias 25-30 (Arquivos/CSV), Dias 32-40 (APIs e JSON).
- **Objetivo:** Manipulação de dados com Pandas/Numpy e criação de APIs com FastAPI.
- **Ferramenta:** PyCharm / VS Code.

### ☁️ Certificação KCNA (Kubernetes and Cloud Native Associate)
- **Estudo:** Teoria do ecossistema CNCF (GitOps, Observabilidade, Orquestração).
- **Frequência:** Leitura leve às sextas-feiras via KodeKloud.
- **Status:** [ ] Pendente

---

## 📅 Fase 2: Infraestrutura Crítica (Mai - Jul)
*O foco é dominar o orquestrador onde o Machine Learning moderno roda.*

### ☸️ Certificação CKA (Certified Kubernetes Administrator)
- **Estudo:** Administração, redes, armazenamento e troubleshooting de clusters.
- **Laboratório:** Montar clusters locais usando Kind ou Minikube no Fedora.
- **Status:** [ ] Pendente

### 📦 Docker & Helm
- **Objetivo:** Empacotamento de aplicações e gerenciamento de pacotes K8s.

---

## 📅 Fase 3: Ciclo de Vida & Observabilidade (Ago - Out)
*O foco é a engenharia de dados aplicada e o monitoramento de modelos.*

### 🧪 MLOps Zoomcamp (DataTalks.Club)
- **Tópicos:** Experiment Tracking (MLflow), Orchestration (Prefect/Mage), Model Serving.
- **Hardware:** Uso da RTX 4070 para treinamento local de modelos.

### 📊 Certificação PCA (Prometheus Certified Associate)
- **Objetivo:** Monitorar a saúde dos modelos e métricas de infraestrutura.
- **Status:** [ ] Pendente

---

## 📅 Fase 4: Expertise Técnica & Escala (Nov - Dez)
*O foco é automação total e especialização sênior.*

### 🔄 Certificação CAPA (ArgoCD Certified Associate)
- **Objetivo:** Implementar GitOps para deploys automáticos de modelos.
- **Status:** [ ] Pendente

### 🏗️ Kubeflow & KServe
- **Projeto Final:** Instalar Kubeflow localmente para gerenciar Pipelines de ML de ponta a ponta.

### 🎓 Certificação CKAD (Certified Kubernetes Application Developer)
- **Objetivo:** Criar manifestos otimizados e gerenciar quotas de recursos (CPU/GPU).
- **Status:** [ ] Pendente

---

## 🛠️ Notas de SRE
- **Monitoramento de Saúde:** Revisar progresso mensalmente no último dia de cada mês.
- **Backup:** Todo código de lab deve ser versionado no diretório correspondente deste repo.
- **Hardware:** Garantir que o NVIDIA Device Plugin esteja configurado no K8s local para uso da GPU.
