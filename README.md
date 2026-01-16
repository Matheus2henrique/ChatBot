# 🤖 ChatBot com IA usando Streamlit e OpenAI

## 📌 Sobre o Projeto

Este projeto consiste em um **ChatBot com Inteligência Artificial** desenvolvido em **Python**, utilizando o **Streamlit** para a interface web e a **API da OpenAI** para geração de respostas inteligentes.

O objetivo principal é permitir uma conversa interativa entre o usuário e a IA, mantendo o **histórico de mensagens** durante a sessão, proporcionando uma experiência semelhante a um chat em tempo real.

Este projeto é ideal para fins de **aprendizado**, **portfólio** e como base para futuras evoluções envolvendo IA conversacional.

---

## 🚀 Funcionalidades

* Interface web simples e intuitiva com Streamlit
* Comunicação com a API da OpenAI
* Envio e recebimento de mensagens em tempo real
* Manutenção do histórico de conversa usando `session_state`
* Separação clara entre mensagens do usuário e da IA

---

## 🛠️ Tecnologias Utilizadas

* **Python**
* **Streamlit**
* **OpenAI API**
* **GPT-4o** (modelo de linguagem)

---

## 📂 Estrutura do Projeto

```bash
📁 chatbot-ia
 ├── app.py          # Arquivo principal da aplicação
 ├── README.md       # Documentação do projeto
```

---

## ⚙️ Pré-requisitos

Antes de executar o projeto, é necessário ter instalado:

* Python 3.9 ou superior
* Conta na OpenAI com uma **API Key válida**

---

## 📦 Instalação

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/chatbot-ia.git
```

2. Acesse a pasta do projeto:

```bash
cd chatbot-ia
```

3. Instale as dependências:

```bash
pip install streamlit openai
```

---

## 🔑 Configuração da API Key

No arquivo principal do projeto, insira sua chave da OpenAI:

```python
modelo = OpenAI(api_key="API_OPENAI")
```

⚠️ **Importante:** Nunca exponha sua API Key em repositórios públicos.

---

## ▶️ Como Executar

Execute o comando abaixo no terminal:

```bash
streamlit run app.py
```

Após isso, o aplicativo será aberto automaticamente no navegador.

---

## 🧠 Como Funciona

* O usuário digita uma mensagem no campo de chat
* A mensagem é armazenada no `session_state`
* Todo o histórico é enviado para a API da OpenAI
* A IA gera uma resposta baseada no contexto da conversa
* A resposta é exibida na interface e salva no histórico

---

## 🔮 Possíveis Melhorias Futuras

* Autenticação de usuários
* Salvamento do histórico em banco de dados
* Estilização personalizada da interface
* Controle de limite de mensagens
* Seleção de diferentes modelos de IA

---

## 👨‍💻 Autor

Projeto desenvolvido para fins de estudo e evolução em **Inteligência Artificial**, **Python** e **desenvolvimento de aplicações web**.

---

⭐ Se este projeto te ajudou, considere dar uma estrela no repositório!
