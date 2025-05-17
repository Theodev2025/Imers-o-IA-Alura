# Agente de IA para Análise de Tendências do Mercado de Ações

Este projeto utiliza agentes de IA e a API do Google para analisar tendências no mercado de ações. Ele permite que você obtenha rapidamente informações relevantes sobre uma ação específica, incluindo notícias, análises e dados históricos.

## Funcionalidades

* **Busca de Informações:** O sistema utiliza um agente de busca (`agente_buscador_acoes`) para coletar dados sobre uma ação, usando a busca do Google (`google_search`).
* **Análise de Tendências:** Um agente analista (`agente_analista_acoes`) processa as informações coletadas para identificar tendências de alta ou baixa, fatores que influenciam o preço da ação e possíveis previsões.
* **Interface Simples:** O usuário fornece o ticker da ação, e o sistema apresenta uma análise formatada em Markdown.

## Como Funciona

1.  O usuário insere o ticker da ação que deseja analisar.
2.  O `agente_buscador_acoes` busca informações relevantes no Google.
3.  O `agente_analista_acoes` analisa as informações e gera um relatório de tendência.
4.  O relatório é apresentado ao usuário.

## Tecnologias Utilizadas

* **Google Gemini:** Modelo de linguagem avançado para os agentes de IA.
* **Google ADK (Agent Development Kit):** Framework para criar e gerenciar agentes de IA.
* **Google Search API:** Ferramenta para realizar buscas no Google.
* **Python:** Linguagem de programação principal.

## Dependências

* `google-genai`
* `google-adk`

## Configuração

1.  Certifique-se de ter uma API Key do Google Gemini.
2.  Configure a API Key utilizando o Google Colaboratory Secrets ou outra forma segura de armazenamento.

## Uso

1.  Execute o código em um ambiente Python (preferencialmente Google Colaboratory).
2.  Insira o ticker da ação quando solicitado.
3.  Aguarde a análise gerada pelo sistema.

## Exemplo

```python
# (Código do projeto fornecido)
