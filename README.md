# 🧠 Analisador de Transações com IA

Este projeto utiliza inteligência artificial para analisar e categorizar transações financeiras automaticamente. Ele lê arquivos JSON com dados de transações e aplica modelos de linguagem (LLMs) para identificar padrões, sentimentos e categorias, tornando a gestão financeira mais inteligente e prática.

## 🚀 Funcionalidades

- 📂 Leitura de arquivos `.json` com transações
- 🤖 Classificação automática por categoria
- 🧠 Análise de sentimentos para entender padrões emocionais nas compras
- 🔍 Seleção de modelo LLM
- 📊 Contador de tokens para otimizar custo com APIs

## 🛠 Estrutura do Projeto

```
analisador-json/
├── analisador_json.py        # Lê e prepara o arquivo de transações
├── transacoes.json           # Exemplo de dados
main.py                       # Ponto de entrada
analisador.py                 # Analisa e responde com IA
categorizador.py              # Organiza transações por categoria
contador_token.py             # Conta tokens para API
selecao_model.py              # Permite escolha de modelo
analisador_sentimentos.py     # Detecta emoções nas transações
```

## 📦 Requisitos

- Python 3.10+
- openai
- dotenv

Instale com:

```bash
pip install -r requirements.txt
```

## 🧪 Como usar

```bash
python main.py
```

Você será guiado com prompts no terminal para carregar o arquivo e realizar as análises.

## 📄 Licença

MIT © Kleber Willians
