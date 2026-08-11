# Gerador de IA 🤖

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)

## Sobre o Projeto ✨

Este é um projeto desenvolvido como parte do meu aprendizado no [DevClub](https://www.devclub.com.br/). O "Gerador de IA" é uma ferramenta web interativa que permite aos usuários gerar texto ou respostas utilizando a **Groq API**.

Com este projeto, demonstro minhas habilidades na integração de APIs externas em aplicações front-end, manipulação de DOM com JavaScript, e a importância da segurança no gerenciamento de chaves de API. É um exemplo prático de como construir interfaces que interagem com serviços de inteligência artificial.

---

## 💻 Tecnologias Utilizadas

Aqui estão as tecnologias que utilizei para construir este projeto:

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Groq](https://img.shields.io/badge/Groq-000000?style=for-the-badge&logo=groq&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## ✨ Funcionalidades

*   **Geração de Texto/Respostas:** Interage com a Groq API para processar inputs do usuário e retornar conteúdo gerado por IA.

*   **Interface Intuitiva:** Design amigável para facilitar a entrada de prompts e visualização das respostas.

*   **Integração de API:** Demonstra o consumo de serviços externos de IA em uma aplicação web.

*   **Manipulação de DOM:** Atualização dinâmica da interface do usuário com as respostas da IA.

---

## 📸 Visualização do Projeto

Confira uma captura de tela do projeto:

<p align="center">
  <img src="https://raw.githubusercontent.com/lucaspalmasanches/Gerador-de-IA/main/img/GeradorComIA.PNG" alt="Gerador de IA" width="80%">
</p>

---

## 🚀 Como Rodar o Projeto (Localmente)

Para rodar este projeto em sua máquina local, siga os passos abaixo. Este projeto requer uma chave de API da Groq para funcionar.

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/lucaspalmasanches/Gerador-de-IA.git
    ```

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd Gerador-de-IA
    ```

3.  **Configurar a Chave de API da Groq (Essencial):**
    *   **Importante:** A chave de API é uma informação sensível e **não deve ser commitada no Git**. Este repositório já está configurado com um arquivo `.gitignore` para ignorar o arquivo `.env`.
    *   Para que o projeto funcione localmente, é necessário fornecer sua própria chave de API da Groq.
    *   **Crie um arquivo chamado `.env`** na raiz do projeto (na mesma pasta do `index.html`).
    *   Dentro do arquivo `.env`, adicione sua chave de API da Groq no seguinte formato:
        ```
        GROQ_API_KEY="SUA_CHAVE_DE_API_DA_GROQ_AQUI"
        ```
        *   **Substitua `"SUA_CHAVE_DE_API_DA_GROQ_AQUI"` pela sua chave real obtida no site da Groq.**
    *   **Observação:** Este projeto acessa a API diretamente do JavaScript no navegador. Para o desenvolvimento local, a chave será lida do ambiente de execução. Para um deploy em produção (ex: GitHub Pages), a prática recomendada é usar um backend (servidor) para intermediar as chamadas à API, protegendo sua chave de ser exposta no código cliente.

4.  **Abra o arquivo `index.html`:**
    *   Simplesmente abra o arquivo `index.html` em seu navegador web preferido para visualizar e interagir com o gerador de IA.

---

## 📚 Aprendizados

Este projeto foi uma experiência valiosa para consolidar meus conhecimentos em:

*   **Integração de APIs:** Consumo de serviços externos de inteligência artificial (Groq API).

*   **JavaScript Avançado:** Manipulação de DOM para criar interfaces interativas e dinâmicas.

*   **Segurança em Desenvolvimento:** A importância de gerenciar chaves de API com `.env` e `.gitignore`.

*   **HTML Semântico e CSS Responsivo:** Criação de estruturas web claras e estilização adaptável.

*   **Controle de Versão:** Gerenciamento eficiente de código com Git e GitHub, incluindo reescrita de histórico para segurança.

---

## Conecte-se Comigo 🤝

Estou sempre aberto a novas conexões e oportunidades. Sinta-se à vontade para entrar em contato!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-palma-sanches-082902426)
[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lucaspalma331@gmail.com)
