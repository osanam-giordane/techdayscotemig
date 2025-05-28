
# 🧭 Roteiro de Aprendizagem: Explorando o GitHub Copilot e Copilot Chat com a Aplicação Exemplo

Este roteiro vai guiar você a usar o **GitHub Copilot** e o **Copilot Chat** para criar e melhorar a aplicação exemplo `techdayscotemig`.  
O foco é praticar, testar sugestões e refletir sobre o uso da IA para desenvolvimento.

---

## 🎯 Objetivos

✅ Entender o que é o **GitHub Copilot** e o **GitHub Copilot Chat**.  
✅ Aprender a usar essas ferramentas para escrever código, refatorar e buscar soluções.  
✅ Aplicar diretamente na **aplicação Flask/Docker**.  
✅ Refletir sobre o uso responsável e eficaz de IA no desenvolvimento.

---

## 1️⃣ O que é o GitHub Copilot?

O GitHub Copilot é um assistente de código alimentado por IA. Ele sugere trechos de código automaticamente enquanto você digita, com base no contexto e comentários.  
Para estudantes, o acesso pode ser **gratuito** através do GitHub Education.  
👉 [https://github.com/education](https://github.com/education)

---

## 2️⃣ O que é o GitHub Copilot Chat?

O **Copilot Chat** é um recurso adicional que permite **falar com a IA em linguagem natural** dentro do VS Code. Você pode:
- Pedir explicações de código
- Solicitar exemplos
- Resolver problemas
- Gerar snippets completos

Para habilitar, instale o **GitHub Copilot Chat** no VS Code.

---

## 3️⃣ Preparação do Ambiente

✅ Crie sua conta no GitHub: [https://github.com/join](https://github.com/join)  
✅ Ative o Copilot: [https://github.com/features/copilot](https://github.com/features/copilot)  
✅ Instale as extensões no VS Code:
- GitHub Copilot
- GitHub Copilot Chat

✅ Abra o projeto no VS Code (`techdayscotemig`)

---

## 4️⃣ Usando o GitHub Copilot no Código

✅ Abra `app/app.py`  
✅ Abaixo do código existente, digite um comentário como:

```python
# Criar uma nova rota que exibe o nome do aluno
```

✅ Veja a sugestão do Copilot e pressione `TAB` para aceitar.

✅ Teste outras sugestões, como:

```python
# Criar uma rota que retorna a data e hora atual
```

✅ Edite a mensagem original do `home()` usando sugestões do Copilot.  
Por exemplo:  
```python
return "Bem-vindo(a) ao TechDays 2025! 🚀"
```

✅ Solicite melhorias no `Dockerfile` (ex: otimização, inclusão de LABEL).

---

## 5️⃣ Usando o Copilot Chat

✅ Abra o painel **Copilot Chat** no VS Code (`Ctrl+Shift+I` ou `Cmd+Shift+I`).  
✅ Faça perguntas como:
- "O que essa função faz?"
- "Como posso criar uma nova rota em Flask?"
- "Como otimizar esse Dockerfile?"
- "Como configurar variáveis de ambiente no Flask?"

✅ Use o Chat para aprender e entender o código.

✅ Experimente pedir **refatorações** e **explicações** no Copilot Chat.  
Exemplo:  
> "Refatore o código para ter mensagens dinâmicas."  
> "Explique o que significa cada linha no Dockerfile."

---

## 6️⃣ Desafios Práticos

✅ Criar novas rotas no Flask com o Copilot:  
- `/aluno` → Exibir seu nome  
- `/curso` → Exibir seu curso  
- `/random` → Exibir um número aleatório  

✅ Usar o Copilot Chat para explicar conceitos:  
- O que é uma rota no Flask?  
- Como criar uma exceção personalizada?  

✅ Criar uma nova branch com as alterações, fazer commit e abrir um Pull Request.

✅ Tentar usar o Copilot para resolver **erros de execução**.

✅ Refletir: O que o Copilot fez bem? O que você precisou ajustar manualmente?

---

## 7️⃣ Recursos para Estudo

📚 [Documentação do GitHub Copilot](https://docs.github.com/pt/copilot)  
📹 [Vídeo - O que é o GitHub Copilot?](https://www.youtube.com/watch?v=FaR6tQ1VMnc&t=176s)   
📚 [Docker Documentation](https://docs.docker.com/)

---

🚀 **Bora praticar!** Lembre-se: o Copilot é seu copiloto, **você é o piloto**. Analise as sugestões, valide, aprenda e **não aceite tudo cegamente**!

---
