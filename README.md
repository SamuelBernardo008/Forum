# 💬 Fórum de Discussões (Flask)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![GitHub Repo Size](https://img.shields.io/github/repo-size/SamuelBernardo008/F-rum)
![GitHub License](https://img.shields.io/github/license/SamuelBernardo008/F-rum?color=blue)

Uma aplicação web de fórum construída em **Python/Flask** para criação de tópicos, troca de ideias e interação entre usuários.

---

## Sobre o Projeto

O **Fórum** é uma plataforma leve e funcional onde os usuários podem criar publicações, interagir através de respostas e gerenciar suas discussões. Foi desenvolvido utilizando o microframework **Flask** para a manipulação de rotas, renderização de templates e lógica do servidor.

---

## Funcionalidades

- [x] **Autenticação de Usuários**: Cadastro, login e controle de sessão.
- [x] **Gestão de Tópicos**: Criação, visualização e listagem de postagens.
- [x] **Respostas / Comentários**: Interação direta nos tópicos criados.
- [x] **Renderização Dinâmica**: Templates HTML/CSS integrados via Jinja2.
- [x] **Categorias & Tags**: Organização de tópicos por assuntos.
- [x] **Perfil de Usuário**: Edição de informações pessoais e histórico de atividades.

---

## Tecnologias Utilizadas

- **Linguagem Principal:** Python 
- **Framework Web:** [Flask](https://flask.palletsproducts.com/)
- **Template Engine:** Jinja2
- **Frontend:** HTML5, CSS3, JavaScript
- **Scripts & Automação:** PowerShell
- **Banco de Dados:** SQLite 

---

## Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter instalado em sua máquina:
- [Python 3.9 ou superior](https://www.python.org/)
- [Git](https://git-scm.com/)

---

### Passo a Passo

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/SamuelBernardo008/F-rum.git
   cd F-rum
   ```

2. **Criar e ativar o ambiente virtual (venv):**

   * **Linux / macOS:**
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

   * **Windows (PowerShell):**
     ```powershell
     python -m venv venv
     .\venv\Scripts\Activate.ps1
     ```

3. **Instalar as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configurar Variáveis de Ambiente:**
   *(Crie um arquivo `.env` na raiz do projeto, se necessário, contendo variáveis como `FLASK_SECRET_KEY` ou credenciais do banco)*

5. **Executar a aplicação:**
   ```bash
   # Opção 1: Executando o script principal
   python app.py

   # Opção 2: Utilizando a CLI do Flask
   flask run
   ```

6. **Acessar no navegador:**
   Abra o endereço [http://127.0.0.1:5000](http://127.0.0.1:5000) no seu navegador.

---

## Como Contribuir

1. Faça um **Fork** do repositório.
2. Crie uma **Branch** para a sua funcionalidade:
   ```bash
   git checkout -b feature/minha-feature
   ```
3. Faça o **Commit** das suas alterações:
   ```bash
   git commit -m 'feat: Adiciona nova funcionalidade'
   ```
4. Envie as alterações para a sua Branch (**Push**):
   ```bash
   git push origin feature/minha-feature
   ```
5. Abra um **Pull Request**.

---

## Licença

Este projeto está sob a licença [MIT](LICENSE).

---

## Contato

Desenvolvido por **Samuel Bernardo** 👋

- **GitHub:** [SamuelBernardo008](https://github.com/SamuelBernardo008)
- **LinkedIn:** [Samuel Bernardo Rodrigues](www.linkedin.com/in/samuelbernardo008)
