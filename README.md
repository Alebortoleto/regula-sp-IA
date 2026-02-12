## 🌐 Demonstração Online
Visualizar protótipo do painel: [CLIQUE AQUI PARA ACESSAR O APP](https://seu-usuario.github.io/regula-sp-IA/)**

---

## 🏗️ Estrutura do Projeto (Arquitetura de IA)

Os processos estão divididos em camadas lógicas para fácil implementação em backend (Python/Node):

* **[Camada 1: Registro e Triagem](./logic/bloco_1_registro_logica.json)**
* **[Camada 2: Motor de Visão](./logic/bloco_2_vistoria_ia.json)**
* **[Camada 3: Liquidação](./logic/bloco_3_encerramento_e_oficinas.json)**
*
* # Regula SP - Ecossistema de Regulação com IA 🚀

Este repositório contém a documentação lógica e a estrutura de dados para a nova plataforma da **Regula SP**, focada em automação de sinistros utilizando Inteligência Artificial Multimodal.

## 📌 Visão Geral
O projeto visa transformar a regulação de sinistros tradicional num processo digital instantâneo, utilizando:
- **Visão Computacional:** Para análise de danos e OCR de documentos.
- **NLP (Processamento de Linguagem Natural):** Para análise de relatos de voz e triagem de sentimentos.
- **Análise Preditiva:** Para score de fraude e aprovação em *Fast Track*.

## 🏗️ Estrutura do Projeto (Blocos de Lógica)

Atualmente, o projeto está a ser documentado por blocos modulares:

### [Bloco 1: Cabeçalho e Registro](./bloco_1_registro_logica.json)
- **Objetivo:** Identificação segura do utilizador e captura do contexto inicial.
- **Tecnologias:** Biometria Facial, Geofencing e OCR de documentos (CNH/CRLV).
- **Diferencial:** Motor de análise de voz para detecção de emergências.

### [Bloco 2: Vistoria Digital](./bloco_2_vistoria_ia.json)
- **Objetivo:** Análise automática de danos usando visão computacional.
- **Tecnologias:** Detecção de objetos, análise de metadados e estimativa de custos por IA.
- **Diferencial:** Guia de captura em tempo real e prevenção de fraudes visuais.
  
### [Bloco 3: Triagem e Encerramento](./bloco_3_encerramento_e_oficinas.json)
- **Objetivo:** Encaminhamento para oficinas, logística e liquidação do sinistro.
- **Tecnologias:** Algoritmos de recomendação, IA Generativa para laudos e integração com APIs de pagamento.
- **Diferencial:** Aprovação instantânea (Fast Track) para casos de baixa complexidade.

## 🛠️ Tecnologias Sugeridas
- **Backend:** Python (FastAPI)
- **IA:** Gemini 1.5 Pro / GPT-4o
- **Database:** PostgreSQL + Pinecone (Vector Search)
- **Frontend:** Flutter (iOS/Android)

---
*Documentação em desenvolvimento por Alessandro Bortoleto Rodrigues.*
