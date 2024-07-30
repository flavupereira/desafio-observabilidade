# Use uma imagem base do Python
FROM python:3.9-slim

# Defina o diretório de trabalho
WORKDIR /app

# Copie o código da aplicação para o contêiner
COPY python-app /app

# Instale as dependências
RUN pip install -r /app/requirements.txt

# Comando para rodar a aplicação
CMD ["python", "/app/app.py"]
