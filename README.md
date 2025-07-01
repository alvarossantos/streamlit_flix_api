# 🎬 Streamlit Flix API 🚀

Bem-vindo ao frontend do **Flix App** **! 🌟 Uma interface web interativa e amigável, construída com Streamlit, para consumir e gerenciar dados da nossa incrível API de Filmes.**

### 🔗 **Backend API**

Este projeto frontend depende totalmente da nossa API backend. Certifique-se de que ela esteja em execução antes de iniciar este aplicativo.
➡️ Repositório do Backend: [**github.com/alvarossantos/flix_api**](https://github.com/alvarossantos/flix_api "null") ⬅️

## 📸 Screenshots

*Tela de Login da aplicação Streamlit*

*Dashboard Principal da aplicação Streamlit*

## ✨ Funcionalidades Principais

* **🔐 Autenticação de Usuário:** Sistema de login seguro para acesso à plataforma.
* **📊 Dashboard Interativo:** Visualize estatísticas e gráficos dinâmicos sobre os filmes, gêneros e avaliações.
* **🎬 Gerenciamento de Filmes:** Adicione, visualize e gerencie todos os filmes da sua coleção.
* **🎭 Gerenciamento de Atores/Atrizes:** Mantenha um catálogo completo de atores e atrizes.
* **📚 Gerenciamento de Gêneros:** Organize os filmes por seus respectivos gêneros.
* **⭐ Sistema de Avaliações:** Permita que os usuários avaliem e comentem sobre os filmes.

## 🛠️ Tecnologias e Ferramentas

**Este projeto foi desenvolvido com o que há de melhor no ecossistema Python para aplicações web de dados:**

* [**Python**](https://www.python.org/ "null") 3.10+ 🐍
* [**Streamlit**](https://streamlit.io/ "null") - Para a construção da interface de forma rápida e interativa. 🎈
* [**Requests**](https://requests.readthedocs.io/en/latest/ "null") - Para realizar as chamadas HTTP para a nossa API. 🌐
* [**Pandas**](https://pandas.pydata.org/ "null") - Para manipulação e exibição de dados. 🐼
* [**Plotly**](https://plotly.com/python/ "null") - Para a criação de gráficos ricos e interativos. 📈
* [**Streamlit-AgGrid**](https://github.com/PablocFonseca/streamlit-aggrid "null") - Para tabelas de dados poderosas e customizáveis. 📜

## 🚀 Como Executar o Projeto

**Para ter o projeto rodando na sua máquina local, siga estes simples passos.**

1. **Clone este repositório:**
   ```
   git clone https://github.com/alvarossantos/streamlit_flix_api.git
   cd streamlit_flix_api

   ```
2. **Crie e ative um ambiente virtual:**
   ```
   # Para Linux/macOS
   python3 -m venv .venv
   source .venv/bin/activate

   # Para Windows
   python -m venv .venv
   .venv\Scripts\activate

   ```
3. **Instale as dependências:**
   ```
   pip install -r requirements.txt

   ```
4. **Inicie o servidor do Streamlit:**
   ```
   streamlit run app.py

   ```
5. **Pronto!** 🤩 Agora é só abrir o seu navegador no endereço `http://localhost:8501`.

## 📂 Estrutura do Projeto

**O projeto é organizado de forma modular para facilitar a manutenção e o desenvolvimento de novas funcionalidades:**

```
streamlit_flix_api/
├── actors/             # Módulo para a página de Atores
│   ├── page.py
│   └── service.py
├── api/                # Módulo de serviço para comunicação com a API
│   └── service.py
├── genres/             # Módulo para a página de Gêneros
├── home/               # Módulo para a Dashboard/Página Inicial
├── login/              # Módulo para a página de Login
├── movies/             # Módulo para a página de Filmes
├── reviews/            # Módulo para a página de Avaliações
├── .streamlit/         # Configurações do Streamlit
│   └── config.toml
├── app.py              # Arquivo principal da aplicação
└── requirements.txt    # Dependências do projeto

```


## 🤝 Contribuindo

**Toda contribuição é muito bem-vinda e apreciada! Se você tem interesse em ajudar a melhorar este projeto, existem várias maneiras de participar.**

### 🐛 Reportando Bugs

Encontrou um problema? Pedimos que, por favor, [**abra uma nova issue**](https://www.google.com/search?q=https://github.com/alvarossantos/streamlit_flix_api/issues "null") detalhando o que aconteceu. Tente incluir:

* **Uma descrição clara e concisa do bug.**
* **Passos para reproduzir o comportamento.**
* **O comportamento esperado.**
* **Screenshots, se aplicável.**

### 💡 Sugerindo Melhorias

**Tem uma ideia para uma nova funcionalidade ou uma melhoria em algo que já existe?**

1. Verifique se já não existe uma [**issue**](https://www.google.com/search?q=https://github.com/alvarossantos/streamlit_flix_api/issues "null") aberta sobre o mesmo assunto.
2. Se não houver, [**abra uma nova issue**](https://www.google.com/search?q=https://github.com/alvarossantos/streamlit_flix_api/issues "null") para que possamos discutir a sua ideia.

### Pull Requests

**Se você já tem o código pronto para corrigir um bug ou implementar uma melhoria:**

1. **Faça um Fork** deste repositório.
2. **Crie uma nova Branch** (`git checkout -b feature/`).
3. **Faça o Commit** das suas alterações (`git commit -m 'Adiciona sua Mensagem'`).
4. **Faça o Push** para a sua branch (`git push origin feature/`).
5. **Abra um Pull Request** e descreva as suas alterações em detalhes.

**Agradecemos o seu interesse em tornar este projeto ainda melhor!**
