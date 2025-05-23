# n8n-smart-tagging
🧠 Automatização inteligente de tags no ActiveCampaign usando n8n, GPT e Webhooks. Classificação dinâmica de produtos e leads com criação automática de tags.


# 🧠 Projeto n8n: Tagueamento Inteligente com OpenAI + ActiveCampaign

Este projeto utiliza o n8n para classificar leads automaticamente com base no produto comprado, atribuindo tags no ActiveCampaign de forma inteligente.

## 💡 Funcionalidades

- Recebe dados de um webhook (formulário de compra).
- Usa GPT (OpenAI) para gerar categoria, objetivo e público-alvo do produto.
- Verifica se as tags já existem no ActiveCampaign.
- Cria tags novas se necessário.
- Cria/atualiza o contato.
- Atribui as tags corretamente.

## 🔗 Stack
- n8n
- OpenAI (GPT)
- ActiveCampaign

## 📸 Prints do Fluxo
Estão na pasta `prints/`

## 🚀 Como importar o workflow

1. Abra o n8n.
2. Clique em "Import".
3. Carregue o arquivo `workflow.json`.

## 📂 Arquivo do fluxo

O arquivo `workflow.json` contém o fluxo exportado diretamente do n8n.
