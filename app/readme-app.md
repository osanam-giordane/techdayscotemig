## 🐍 Aplicação Exemplo para Testes

### Descrição:
Aplicação simples em Python (Flask) para os alunos brincarem com Git, GitHub e Docker.

**Arquivo principal (`app.py`):**
```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "Hello, TechDays! 🚀"

if __name__ == "__main__":
    app.run(host="0.0.0.0", port=5000)
```

**Arquivo de dependências (`requirements.txt`):**
```
flask
```

**Dockerfile:**
```Dockerfile
FROM python:3.11-slim
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
EXPOSE 5000
CMD ["python", "app.py"]
```

**.gitignore:**  
```
__pycache__/
*.py[cod]
*.egg-info/
*.log
*.sqlite3
.env
.venv/
venv/
.vscode/
.idea/
*.swp
*.tar
*.pid
*.sock
.dockerignore
.DS_Store
Thumbs.db
```

---

### Como rodar a aplicação

✅ **Localmente:**  
```bash
cd app
pip install -r requirements.txt
python app.py
```
Acesse: [http://localhost:5000](http://localhost:5000)

✅ **Com Docker:**  
```bash
docker build -t techdays-app .
docker run -d -p 5000:5000 techdays-app
```
Acesse: [http://localhost:5000](http://localhost:5000)

✅ **Desafios para os alunos:**  
- Modificar a mensagem no `app.py`
- Criar uma nova rota `/aluno` que responda com seu nome
- Fazer commits e abrir Pull Requests com as alterações

---