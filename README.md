# 🤖 Automação de Disparo de Mensagens com n8n

> **Status do Projeto:** Concluído ✔️

## 🎯 O Problema
Processos manuais de comunicação consumiam muito tempo, estavam sujeitos a erros humanos e não tinham escalabilidade. Havia a necessidade de orquestrar disparos em massa, respeitando os limites da API para evitar bloqueios (Rate Limits).

## 💡 A Solução (Arquitetura)
Desenvolvimento de um workflow automatizado utilizando **n8n** integrado ao Google Sheets e à Evolution API. A arquitetura inclui leitura de banco de dados, filtragem de status de envio, orquestração de filas (Split in Batches) e pausas programadas.


## 🚀 Impacto e Resultados
* **Otimização de Tempo:** Redução drástica do tempo despendido em tarefas de comunicação passiva.
* **Escalabilidade:** Capacidade de processamento sequencial sem sobrecarregar a API.
* **Controle de Status:** Atualização em tempo real do banco de dados para evitar envios duplicados.

## 📁 Arquivo do Projeto
Para visualizar a lógica completa, faça o download do arquivo `workflow-whatsapp.json` disponível neste repositório e importe-o para a sua instância do n8n.
