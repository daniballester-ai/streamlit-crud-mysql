## CRUD com MySQL: Uma Demonstração Prática com Streamlit 💫

Este repositório demonstra como realizar operações CRUD (Create, Read, Update e Delete) em um banco de dados MySQL utilizando a biblioteca Streamlit para criar uma interface web interativa ✨. 

**Por que usar Streamlit?**

* **Facilidade de uso:** Streamlit permite construir aplicações web com poucas linhas de código, tornando a construção de dashboards e ferramentas interativas simples e rápida 🚀.
* **Interface intuitiva:** O Streamlit fornece componentes prontos para criar interfaces visuais atraentes, com widgets para entrada de dados, exibição de tabelas e gráficos, e mensagens de feedback 🎨.
* **Integração com Python:** Streamlit é totalmente integrado à linguagem Python, facilitando a conexão com bancos de dados e a manipulação de dados 🐍.

**O que este projeto demonstra:**

* Conexão com um banco de dados MySQL utilizando a biblioteca `mysql.connector` 🤝.
* Implementação das operações CRUD (Create, Read, Update e Delete) com SQL 🔨.
* Interface web interativa criada com Streamlit 🤩.

**Como usar o projeto:**

1. **Instale as dependências:**
```bash
pip install streamlit mysql-connector-python
```

2. **Crie um banco de dados MySQL:**
   * Crie um banco de dados chamado "crud_new" e uma tabela chamada "users" com as colunas "id", "name" e "email".
   * Configure as credenciais de acesso ao banco de dados no arquivo `app.py`.

3. **Execute a aplicação:**
```bash
streamlit run app.py
```

4. **Acesse a aplicação:**
   * Abra seu navegador e acesse a URL `http://localhost:8501/`.

**Printscreens do app em execução:**

![Tela inicial do app](https://github.com/daniballester-ai/streamlit-crud-mysql/blob/main/crud-streamlit-mysql.jpg)

**Recursos:**

* **Código fonte:** O código completo está disponível neste repositório.
* **Documentação do Streamlit:** https://docs.streamlit.io/
* **Documentação do MySQL connector:** https://dev.mysql.com/doc/connector-python/en/connector-python-api.html

**O que você pode aprender com este projeto:**

* Como conectar um aplicativo Python a um banco de dados MySQL 🔌.
* Como realizar operações CRUD em um banco de dados 🏗️.
* Como construir uma interface web interativa com Streamlit 💻.
* Como integrar Python e SQL para manipulação de dados 🧠.

**Este projeto é um ótimo ponto de partida para aprender sobre o desenvolvimento web com Python e Streamlit. Você pode expandi-lo adicionando novas funcionalidades, como:**

* Criação de relatórios e visualizações de dados 📊.
* Implementação de autenticação de usuários 🔒.
* Integração com outras APIs 🌐.

**Contribuições:**

Contribuições para este projeto são bem-vindas! Você pode contribuir com correções de bugs, melhorias de código ou novas funcionalidades 💪.

**Espero que este projeto lhe seja útil!** 😄
