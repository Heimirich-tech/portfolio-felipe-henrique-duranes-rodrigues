# 🛠️ Engenharia de Prompt: Prototipagem ImobiFlow SaaS

## 📝 Descrição do Projeto
Este projeto foi desenvolvido como parte da disciplina de **Engenharia de Prompt e Aplicações em IA**. O objetivo principal foi construir e validar um **Prompt Estruturado em XML** altamente especializado para a geração automatizada de uma página única (Single Page Application - SPA) com CSS e JavaScript integrados.

O ecossistema testado simula o MVP do **ImobiFlow SaaS**, um sistema de gestão imobiliária multi-tenant (White Label) focado em corretores autônomos e imobiliárias. O prompt desafia as ferramentas de IA a gerarem simultaneamente uma interface funcional de "Dashboard do Corretor" e uma "Vitrine Pública" mobile-first.

## 🚀 Tecnologias e Modelos Avaliados
O prompt estruturado foi submetido a um protocolo de execução rigoroso e testado comparativamente nas seguintes ferramentas de Inteligência Artificial:

* **Google Gemini**
* **Anthropic Claude**
* **OpenAI ChatGPT (GPT)**
* **DeepSeek**
* **Qwen**
* **xAI Grok**
* **Maritaca AI**

## 🏗️ Requisitos de Regras de Negócio (XML)
O prompt exige que os modelos interpretem e implementem as seguintes regras diretamente na interface gerada:

* **Multi-Tenancy:** Isolamento de dados por `tenant_id` (ex: exibição de logomarca dinâmica).
* **CRM Kanban:** Funil visual para gestão de leads (Novos, Visitas, Propostas).
* **Inventory Management:** Cards de imóveis com status dinâmico (Ativo, Reservado, Vendido).
* **Public View:** Seção de busca rápida e galeria mobile-first com botão flutuante de WhatsApp.

---

## 📊 Quadro de Análise Comparativa
Após a execução do protocolo, os modelos apresentaram variações significativas de performance, qualidade de código e consumo de tokens:

| Critérios de Avaliação | GPT | Gemini | DeepSeek | Qwen | Grok | Maritaca | Claude |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Precisão Estimada do Prompt** | Razoável | **Muito Bom** | Boa | Razoável | Razoável | Horrível | **Muito Bom** |
| **Precisão do HTML** | Razoável | **Muito Precisa** | Razoável | Razoável | Razoável | Ruim | **Muito Precisa** |
| **Criatividade no Conteúdo** | Boa | **Excelente** | Bom | Ruim | Bom | Ruim | **Excelente** |
| **Erros de Sintaxe (Bugs)** | Nenhum | **Nenhum** | Alguns | Muitos | Nenhum | Inúmeras | **Nenhum** |
| **Quantidade de Tokens Gasta** | 2100 | **1850** | 1590 | 2300 | 4850 | 2450 | 12200 |

---

## 🧠 Reflexão Crítica & Aprendizados

* **Compreensão Estrutural:** Os modelos **Gemini** e **Claude** demonstraram a maior capacidade de interpretação e respeito à estrutura de tags do prompt em XML.
* **Verbosidade e Eficiência:** Houve uma diferença brutal no consumo de tokens entre as IAs. Enquanto o Gemini entregou um resultado excelente com apenas 1.850 tokens, o Claude consumiu 12.200 tokens para entregar o mesmo escopo de projeto.
* **Veredito de Escolha:** Com base nos testes práticos, o **Gemini** e o **Claude** consolidam-se como as ferramentas ideais tanto para prototipagem rápida quanto para o desenvolvimento de códigos altamente complexos e estruturados.

## 👥 Integrantes do Projeto
* Felipe Henrique Duranes Rodrigues
* Felipe André Cruz Leite
* Vitor da Silva Bonilha

---
[⬅️ Voltar ao início](https://github.com/seu-usuario/Tecnologia-Heimirich)
