# Career-Lens

Plataforma de inteligência de carreira com IA para analisar perfis profissionais, comparar requisitos de vagas e identificar gaps de competências.

## 🎯 Problema

Profissionais frequentemente têm dificuldade para avaliar de forma objetiva como suas experiências e competências se relacionam com as exigências de uma vaga.

Currículos apresentam experiências em linguagem livre, enquanto vagas descrevem requisitos com terminologias, níveis de senioridade e tecnologias diferentes.

O Career-Lens nasce para reduzir essa distância por meio de análise estruturada apoiada por Inteligência Artificial.

## 💡 Solução

O Career-Lens terá como objetivo:

- analisar um perfil profissional;
- interpretar requisitos de uma vaga;
- identificar competências existentes;
- identificar competências ausentes ou pouco evidentes;
- comparar perfil e vaga;
- gerar um relatório de gaps;
- sugerir uma trilha de evolução profissional.

O desenvolvimento será incremental, adicionando novas capacidades de IA conforme o projeto evolui.

## 🏗️ Arquitetura

A arquitetura será construída progressivamente.

Fluxo planejado:

Perfil profissional  
↓  
Extração e normalização de competências  
↓  
Análise da vaga  
↓  
Comparação perfil × requisitos  
↓  
Gap Analysis  
↓  
Recomendações de desenvolvimento

Componentes avançados como RAG, agentes, MCP e Evaluation serão incorporados em versões futuras.

## 🧠 RAG

Status: Planejado

O projeto utilizará Retrieval-Augmented Generation para permitir que os modelos consultem informações externas e gerem respostas fundamentadas em fontes relevantes.

## 🤖 AI Agent

Status: Planejado

Uma camada de agentes será adicionada para coordenar tarefas como:

- análise do perfil;
- análise da vaga;
- consulta ao conhecimento;
- execução de ferramentas;
- geração de recomendações.

## 🔌 MCP

Status: Planejado

O Model Context Protocol será estudado e incorporado ao projeto para permitir que agentes acessem ferramentas e fontes de dados através de interfaces padronizadas.

## 📊 Evaluation

Status: Planejado

O Career-Lens possuirá uma camada de avaliação para medir a qualidade das respostas geradas pela IA.

Entre os aspectos avaliados estarão:

- relevância;
- groundedness;
- qualidade da recuperação;
- identificação correta de competências;
- precisão da análise de gaps.

## 🛠️ Tecnologias

Tecnologias previstas:

- Python
- Large Language Models
- RAG
- Vector Search
- AI Agents
- MCP
- Evaluation
- APIs
- Git
- GitHub

A stack poderá evoluir conforme as necessidades técnicas do projeto.

## 📁 Estrutura do projeto

A estrutura será criada durante a evolução do desenvolvimento.

Exemplo planejado:

career-lens/

├── src/  
├── data/  
├── tests/  
├── docs/  
├── evaluation/  
├── README.md  
└── LICENSE

## 🧪 Testes

Os testes serão adicionados progressivamente.

O objetivo é validar tanto o código tradicional quanto os componentes baseados em IA.

## 🚀 Roadmap

### v0.1 — Definição do problema

- [x] Criação do repositório
- [x] Definição inicial do problema
- [x] Definição da visão do projeto
- [x] Roadmap inicial

### v0.2 — RAG

- [ ] Preparação dos dados
- [ ] Chunking
- [ ] Embeddings
- [ ] Vector Store
- [ ] Retrieval
- [ ] Respostas fundamentadas

### v0.3 — AI Agent

- [ ] Definição do agente
- [ ] Tools
- [ ] Orquestração
- [ ] Integração com RAG

### v0.4 — MCP

- [ ] Criação de servidor MCP
- [ ] Definição de ferramentas
- [ ] Integração do agente com MCP

### v0.5 — Evaluation

- [ ] Dataset de avaliação
- [ ] Métricas
- [ ] Groundedness
- [ ] Avaliação das respostas
- [ ] Testes automatizados

### v1.0 — Career-Lens

- [ ] Pipeline completo
- [ ] Análise de perfil
- [ ] Análise de vaga
- [ ] Gap Analysis
- [ ] Recomendações
- [ ] RAG
- [ ] Agent
- [ ] MCP
- [ ] Evaluation

## 👤 Autor

**Gilson Ravaiani**

Projeto desenvolvido como laboratório prático de AI Engineering e evolução profissional.
