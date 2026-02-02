# Passo a passo da execução

Esta pasta contém o código do seu agente financeiro.

## Setup do Ollama

```
1. Instalar o Ollama (ollama.com)
2. Baixar um modelo leve sugerido até 20gb
ollama pull glm-4.7-flash

3. Testar para ver se esta funcionando
ollama run glm-4.7-flash "Olá"
```
## Código Completo

todo o codigo fonte está no `app.py`.

## Exemplo de requirements.txt

```
streamlit
pandas
requests
```

## Como Rodar

```bash
# 1. Instalar dependências
pip install -r requirements.txt oou pip install streamlit pandas requests

# 2. Garantir que o Ollama está rodando
ollama serve

# 3. Rodar o app
streamlit run app.py (dentro do diretorio src)
```
