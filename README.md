# 🧠 Desafio 01: Imersão em IA Generativa com NotebookLM

<p align="center">
  <img src="imagem.png" alt="NotebookLM" width="1000">
</p>


> **Descrição:** Desenvolvimento de um manual didático e abrangente sobre Inteligência Artificial, focado em simplificar a jornada de iniciantes no universo da IA Generativa aplicada a dados.

---

## 🔗 Acesso ao Projeto
Você pode visualizar o projeto completo e interagir com as fontes diretamente através do link abaixo:

> [**Acessar NotebookLM - Manual de IA**](https://notebooklm.google.com/notebook/afc79a06-9278-4f8f-8e5c-eef795755335)

## 📌 Sumário
1. [Sobre o Projeto](#-sobre-o-projeto)
2. [Objetivos do Manual](#-objetivos-do-manual)
3. [Base de Conhecimento (Fontes)](#-base-de-conhecimento-fontes)
4. [Metodologia de Estudo](#-metodologia-de-estudo)
5. [Principais Insights](#-principais-insights)
6. [Como Utilizar este Repositório](#-como-utilizar-este-repositório)
7. [Autor](#-autor)


---


## 📖 Sobre o Projeto

Este repositório é o resultado de uma imersão profunda na interseção entre **IA Generativa** e **Análise de Dados**. Utilizando o potencial do **Google NotebookLM**, processei documentos governamentais, acadêmicos e técnicos para criar um manual que traduz a complexidade da IA para uma linguagem acessível e estratégica.

O projeto não apenas sintetiza informações, mas estrutura um caminho de aprendizado para quem deseja expandir habilidades em uma das áreas mais crescentes da tecnologia atual.


## 🎯 Objetivos do Manual

*   **Aceleração de Curva de Aprendizado:** Facilitar o entendimento de termos técnicos (LLMs, RAG, Tokens) para leigos.
*   **Soberania Digital:** Basear o conhecimento em planos nacionais (PBIA 2025) e diretrizes éticas.
*   **Aplicação Prática:** Mostrar como a IA pode ser usada para extrair insights valiosos de grandes volumes de dados.


## 📚 Base de Conhecimento (Fontes)

A curadoria deste manual foi baseada em fontes de alto rigor técnico e institucional:


| Fonte | Instituição | Tipo de Documento |
| :--- | :--- | :--- |
| [IA em Data Analytics](https://cloud.google.com/use-cases/ai-data-analytics?hl=pt-BR) | Google Cloud | Guia de Caso de Uso |
| [PBIA 2025](https://www.gov.br/mcti/pt-br/centrais-de-conteudo/publicacoes-mcti/plano-brasileiro-de-inteligencia-artificial/pbia_mcti_2025.pdf) | MCTI | Plano Nacional |
| [Aplicação de IA](https://repositorio-api.animaeducacao.com.br/server/api/core/bitstreams/5d8f1cbd-0a29-440b-9a67-a13a58ece747/content) | Anima | E-book |
| [Ferramentas e Desafios](https://adapta.org/blog/ia-para-analise-de-dados) | ADAPTA | Guia |


## 🛠️ Metodologia de Estudo

1.  **Ingestão de Dados:** Carregamento das fontes citadas no motor do NotebookLM.
2.  **Processamento Semântico:** Cruzamento de dados entre o Plano Brasileiro (PBIA) e aplicações práticas do Google Cloud.
3.  **Refinamento de Prompts:** Utilização de técnicas de *Prompt Engineering* para extrair resumos didáticos e guias de "passo a passo".
4.  **Estruturação de Manual:** Organização do output em um guia lógico de introdução, desenvolvimento e conclusão.


## ✨ Principais Insights Gerados

- A importância da **ética e governança** conforme o Plano Brasileiro de IA.
- Como a IA Generativa reduz o tempo de **limpeza e preparação de dados** em até 60%.
- O papel fundamental da IA na **Indústria 4.0** para pequenos e médios negócios (Sebrae).


## 📂 Como Utilizar este Repositório
*   `notebooks/`: Contém os logs ou resumos exportados do NotebookLM.
*   `referencias/`: Links e PDFs utilizados como fonte primária.
*   `README.md`: Guia principal de navegação.


---


## 👤 Autor

Desenvolvido por **Michael Pires** – Sinta-se à vontade para se conectar!

[![LinkedIn](https://img.icons8.com/?size=48&id=13930&format=png)](https://www.linkedin.com/in/michael-pires-897615200/)
[![GitHub](https://img.icons8.com/?size=48&id=AZOZNnY73haj&format=png)](https://github.com/MichaelJPires)

---
⭐️ Se este guia te ajudou, dê uma **estrela** no repositório!





Para o seu repositório no GitHub, o tópico de Engenharia de Prompts (o item 3 da DIO) precisa mostrar que você não apenas "conversou" com a IA, mas que testou limites e refinou a comunicação.
Aqui está uma elaboração "mais humana" e técnica, conectada ao seu tema de IA na Análise de Dados, para você copiar e adaptar:
------------------------------
3. Engenharia de Prompts e "Cicatrizes" de Aprendizado 🧠
Nesta etapa, documentei a evolução da minha interação com o NotebookLM. O objetivo foi transformar a teoria bruta sobre o ciclo de vida dos dados em insights aplicáveis. Abaixo, detalho os testes, os erros e os ajustes de rota:
🛠️ O Prompt de "Aquecimento" (Onde comecei)

Prompt: "Resuma as fases do ciclo de vida da análise de dados descritas no texto."


* Resultado: A IA entregou uma lista genérica. Faltou profundidade sobre o impacto financeiro (Token Burn) e a diferença estratégica entre modelos.
* Aprendizado: Prompts abertos geram respostas superficiais. Para análise de dados, a precisão é fundamental.

🎯 O Prompt de "Mestre" (Refinado para o Tema)

Prompt: "Aja como um Arquiteto de Soluções GenAI. Com base nas fontes, elabore um plano de ação para uma empresa que precisa escolher entre RAG e Fine-tuning. Considere a volatilidade dos dados e o custo de infraestrutura mencionado no tópico de Sustentabilidade."


* Resultado: Excelente. A IA conectou a necessidade de dados dinâmicos com o "Padrão Ouro" do RAG e alertou sobre o consumo de água/energia dos servidores.
* Por que funcionou? Atribuí uma persona (Arquiteto) e dei contexto restrito (Sustentabilidade e Custo).

🩹 Minhas "Cicatrizes" (Troubleshooting)
Durante o desenvolvimento, enfrentei dois desafios principais:

   1. Alucinação Contextual: Ao perguntar sobre o Plano Brasileiro de IA (PBIA), a IA misturou dados de planos antigos. Solução: "Ancorei" o prompt exigindo que ela citasse especificamente o valor de R$ 23,03 bilhões presente no texto fonte.
   2. Ambiguidade Técnica: A IA confundiu "limpeza de dados" com "redação de dados (masking)". Tive que criar um prompt corretivo definindo que, neste caderno, Redação refere-se à privacidade (LGPD) e não à edição de texto.

------------------------------
4. Miniguia de Estudo: O Futuro da Análise 📖
Este é o consolidado final do meu aprendizado, estruturado para consultas rápidas:
📌 Resumo Executivo
A análise de dados deixou de ser um processo de "olhar para o passado" para se tornar uma camada agêntica e preditiva. A grande virada de chave é a transição do analista "operador de SQL" para o Analista Aumentado, que foca 80% menos em limpeza manual (agora automatizada semanticamente) e 100% mais em governança e estratégia.
📙 Glossário de Termos-Chave

* Token Burn: O consumo de recursos (financeiros e computacionais) ao processar grandes volumes de texto em LLMs.
* RAG (Retrieval-Augmented Generation): Técnica que "alimenta" a IA com documentos externos em tempo real para evitar mentiras (alucinações).
* Soberania Tecnológica: A capacidade de um país (ou empresa) de processar seus dados em infraestrutura própria ou controlada (ex: Supercomputador Pégaso).
* NLQ (Natural Language Querying): Capacidade de fazer perguntas complexas ao banco de dados usando linguagem humana comum.

🚀 Prompts Reutilizáveis para Analistas

* "Analise este pipeline de ETL e identifique pontos onde a LGPD exige a técnica de Perturbação (Ruído) para proteção de PII."
* "Crie uma narrativa executiva (Data Storytelling) comparando o ROI esperado entre o uso de GPT-4o e Gemini 1.5 Pro para este dataset."











