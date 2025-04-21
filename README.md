
# Projeto: Integrando o ChatGPT com Node.js e React ⚡🧠

## 📒 Descrição
Este projeto foi desenvolvido como parte do desafio da DIO com o objetivo de construir uma aplicação web fullstack que integra o **ChatGPT** utilizando a API oficial da **OpenAI**, com **Node.js** no back-end e **React** no front-end.

A proposta é criar um ambiente de conversação inteligente, com uma interface moderna, responsiva e funcional, permitindo interações com a IA de forma natural e fluida.

## 💻 Tecnologias Utilizadas
- **Node.js** — servidor back-end
- **Express.js** — gerenciamento de rotas
- **OpenAI API** — integração com a IA generativa do ChatGPT
- **React** — construção da interface de usuário
- **Vite** — estruturação rápida do front-end
- **Axios** — comunicação HTTP
- **Dotenv** — gerenciamento de variáveis de ambiente

## 🚀 Como Executar o Projeto
### 1. Clone o repositório
```bash
git clone https://github.com/galafis/Integrando-o-ChatGPT-com-Node-e-React.git
cd Integrando-o-ChatGPT-com-Node-e-React
```

### 2. Configure as variáveis de ambiente
Crie um arquivo `.env` na pasta `server` com a seguinte chave:
```env
OPENAI_API_KEY=sua_chave_aqui
```

### 3. Instale as dependências
**Back-end:**
```bash
cd server
npm install
```

**Front-end:**
```bash
cd ../client
npm install
```

### 4. Execute os servidores
**Back-end:**
```bash
cd server
npm run dev
```

**Front-end:**
```bash
cd ../client
npm run dev
```

Abra o navegador em `http://localhost:5173`

## ✨ Funcionalidades
- Interface semelhante ao ChatGPT
- Comunicação em tempo real com a IA da OpenAI
- Estrutura preparada para expandir com histórico, login e melhorias visuais

## 🧠 Engenharia de Prompt
A aplicação permite customizar os prompts enviados à API, simulando diferentes papéis e estilos de resposta.

Exemplo:
> "Aja como um mentor de tecnologia experiente. Responda com paciência e clareza."

## 🌍 Links Úteis
- [Documentação oficial da OpenAI](https://openai.com/blog/chatgpt)
- [Repositório base do Expert](https://github.com/felipeAguiarCode/node-react-chatgpt-clone)

## 📚 Aprendizados
- Integração de API externa com back-end
- Comunicação eficiente entre front e back-end
- Compreensão prática da arquitetura fullstack moderna
- Aplicação real para o portfólio profissional

---

> Projeto desenvolvido com entusiasmo e curiosidade por IA. Compartilhe sua versão com a hashtag **#ChatGPTCloneDIO**!


