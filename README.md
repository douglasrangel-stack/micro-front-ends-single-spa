# Single-SPA Microfrontend Application

## 🚀 Projeto

Este repositório contém a configuração base para uma aplicação **microfrontend** usando o framework **[Single-SPA](https://single-spa.js.org/)**. A arquitetura é composta por múltiplos microfrontends independentes que podem ser desenvolvidos, implantados e escalados separadamente.

---

## 📂 Estrutura do Projeto

A estrutura do repositório é organizada para facilitar o desenvolvimento e integração dos microfrontends:

```plaintext
├── /root         # Configuração principal do Single-SPA
├── package.json         # Dependências e scripts
├── README.md            # Este documento
```

---

## 🛠️ Pré-requisitos

Certifique-se de ter os seguintes softwares instalados em sua máquina:

- [Node.js](https://nodejs.org/) (>= 14.x)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

---

## 📦 Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/douglasrangel-stack/micro-front-ends-single-spa
   cd micro-front-ends-single-spa
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Navegue até cada microfrontend (caso estejam no repositório) e instale as dependências deles:
   ```bash
   cd ./react-login
   npm install
   ```

---

## 🏃‍♂️ Executando o Projeto

1. Inicie o **root**:

   ```bash
   npm start
   ```

2. Inicie cada microfrontend em suas respectivas portas (exemplo para `react-login`):

   ```bash
   cd ./react-login
   npm start
   ```

3. Acesse a aplicação no navegador:
   ```
   http://localhost:9000
   ```

---

## ✨ Funcionalidades

- **Configuração centralizada**: O `root` gerencia a composição de microfrontends.
- **Independência tecnológica**: Cada microfrontend pode ser desenvolvido com uma stack de tecnologia diferente (React, Vue, Angular, etc.).
- **Integração simplificada**: Baseado na arquitetura de aplicações de front-end modulares.

---

## 📖 Documentação

- [Single-SPA - Documentação Oficial](https://single-spa.js.org/docs/getting-started-overview)
- [Configuração de Root](https://single-spa.js.org/docs/configuration/)
- [Guia de Microfrontends](https://micro-frontends.org/)

---

## 🧪 Testes

Este projeto utiliza [Jest](https://jestjs.io/) para testes. Para executar os testes:

```bash
npm test
```

---

## 🛠️ Contribuição

Se você deseja contribuir com este projeto:

1. Faça um fork do repositório.
2. Crie uma branch com suas alterações:
   ```bash
   git checkout -b minha-feature
   ```
3. Commit suas alterações:
   ```bash
   git commit -m "Minha nova feature"
   ```
4. Envie para a branch principal:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License**. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

---

## 📧 Contato

Se você tiver dúvidas ou sugestões, entre em contato:

- Email: **contato@douglasrangel.com**
- LinkedIn: [Douglas Rangel](https://www.linkedin.com/in/douglasrangel/)
