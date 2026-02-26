# Mauricio Palpites (Mobile Web - Streamlit)

## Rodar local
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Hospedar grátis (sem pagar)
### Streamlit Community Cloud
1. Suba este projeto para um repositório no GitHub (app.py + requirements.txt)
2. Acesse o Streamlit Cloud e conecte no repo
3. Escolha o arquivo `app.py` para deploy

### Hugging Face Spaces (Streamlit)
1. Crie um Space com SDK = Streamlit
2. Suba `app.py` e `requirements.txt`

## Token
O app já vem com token default de football-data.
Se quiser, você pode sobrescrever via Secrets/Env usando `FOOTBALL_DATA_TOKEN`.
