# 🤖 Automação de Relatórios com n8n + IA

Sistema automatizado de análise e geração de relatórios de vendas.

## 📊 Funcionalidades
- Análise estatística automática de vendas
- Geração de relatórios com IA
- Dashboard visual com insights
- Integração com n8n para automação

## 🛠️ Tecnologias
- Python 3.x
- Pandas / NumPy
- Google Gemini AI
- n8n (automação)

## 🚀 Como Executar
```bash
pip install -r requirements.txt
python scripts/main.py
```
# Adicionar seção n8n ao README
n8n_section = """

## 🔄 INTEGRAÇÃO COM n8n (AUTOMAÇÃO)

### 📋 Fluxo de Trabalho Implementado
Este projeto está preparado para automação com [n8n](https://n8n.io/), uma plataforma de automação de workflows.

#### Fluxo Principal:
1. **Trigger**: Manual ou agendado (ex: toda segunda-feira 9AM)
2. **Entrada de Dados**: Arquivo CSV local ou Google Sheets
3. **Processamento**: Script Python (`analise_vendas.py`)
4. **IA**: Geração de insights com modelo de linguagem
5. **Saída**: Email, Slack, WhatsApp, ou Google Drive

### 🛠️ Como Configurar o n8n

#### Opção 1: n8n.cloud
```bash
1. Acesse https://n8n.cloud
2. Crie conta gratuita
3. Importe o workflow: n8n_workflows/automation_workflow.json
4. Configure credenciais:
   - Email SMTP (para envio)
   - Google Sheets/Drive (opcional)
5. Execute o fluxo!
