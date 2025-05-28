# Usar uma imagem base do Python
FROM python:3.11-slim

# Definir diretório de trabalho
WORKDIR /app

# Copiar arquivos para o container
COPY . .

# Instalar dependências
RUN pip install -r requirements.txt

# Expor a porta que a aplicação usa
EXPOSE 5000

# Definir o comando de inicialização
CMD ["python", "app.py"]
