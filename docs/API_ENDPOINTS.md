# Documentação dos Endpoints da API

Esta documentação descreve como usar os endpoints da aplicação para integração com o n8n.

## 📋 Índice

1. [Endpoint: Enviar Mensagem para n8n](#1-endpoint-enviar-mensagem-para-n8n)
2. [Endpoint: Webhook para Receber Resposta do n8n](#2-endpoint-webhook-para-receber-resposta-do-n8n)
3. [Endpoint: Status da Resposta (Polling)](#3-endpoint-status-da-resposta-polling)
4. [Configuração do n8n](#4-configuração-do-n8n)
5. [Exemplos de Uso](#5-exemplos-de-uso)

---

## 1. Endpoint: Enviar Mensagem para n8n

**URL:** `POST /api/chat`

**Descrição:** Este endpoint recebe mensagens do frontend e as encaminha para o webhook do n8n.

