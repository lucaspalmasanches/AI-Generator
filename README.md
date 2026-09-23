# AI Content Generator 🤖

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## About the Project ✨

This project was developed as part of my learning journey at [DevClub](https://www.devclub.com.br/), with the goal of creating an **Artificial Intelligence-based content generator**. Utilizing the Groq API, this tool allows users to input a prompt and receive an AI-generated response, demonstrating the integration of language models into simple web applications.

With this project, I aim to consolidate my knowledge in consuming external APIs, asynchronous JavaScript for handling requests, and basic DOM manipulation to display results. It's a practical example of how to integrate AI technologies into user interfaces.

---

## 💻 Technologies Used

Here are the technologies I used to build this project:

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Groq API](https://img.shields.io/badge/Groq%20API-FF4081?style=for-the-badge&logo=react&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-00599C?style=for-the-badge&logo=rest&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## ✨ Features

*   **AI Content Generation:** Sends user prompts to the Groq API and displays the generated response.

*   **External API Integration:** Consumption of Artificial Intelligence services for dynamic functionalities.

*   **Intuitive User Interface:** Simple design to facilitate text input and response viewing.

*   **Asynchronous JavaScript:** Management of API requests in a non-blocking manner.

*   **Secure API Key Management:** Implementation of the API key using environment variables.

---

## 📸 Project Visualization

Check out a screenshot of the AI generator:

<p align="center">
  <img src="https://raw.githubusercontent.com/lucaspalmasanches/AI-Generator/main/img/GeradorComIA.PNG" alt="AI Generator - Desktop Version" width="50%">
</p>

---

## 🚀 How to Run the Project (Locally)

To run this project on your local machine, follow the steps below. This project requires a Groq API key to function.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/lucaspalmasanches/AI-Generator.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd AI-Generator
    ```

3.  **Configure the Groq API Key (Essential):**
    *   **Important:** The API key is sensitive information and **must not be committed to Git**. This repository is already configured with a `.gitignore` file to ignore `.env`.
    *   For the project to work locally, you need to provide your own Groq API key (obtained for free from their website).
    *   **Create a file named `.env`** in the root of the project (in the same folder as `index.html`).
    *   Inside the `.env` file, add your API key in the following format:
        ```
        GROQ_API_KEY="YOUR_GROQ_API_KEY_HERE"
        ```
        *   **Replace `"YOUR_GROQ_API_KEY_HERE"` with your actual key.**
    *   **Note:** This project accesses the API directly from JavaScript in the browser. For local development, the key will be read from the execution environment. For a production deployment (e.g., GitHub Pages), the recommended practice is to use a backend (server) to mediate calls to the API, protecting your key from being exposed in client-side code.

4.  **Open the `index.html` file:**
    *   Simply open the `index.html` file in your preferred web browser to view and interact with the AI generator.

---

## 📚 Learnings

This project was a valuable and challenging experience, consolidating my knowledge in:

*   **External API Consumption:** Integration with Artificial Intelligence services for dynamic functionalities.

*   **Asynchronous JavaScript:** Use of `fetch` and `async/await` to handle API requests efficiently.

*   **DOM Manipulation:** Dynamic updating of the user interface to display AI responses.

*   **Security in Development:** The importance and correct implementation of API key management with `.env` and `.gitignore`.

*   **Semantic HTML and Basic CSS:** Clear web content structuring and styling for a functional user interface.

*   **Version Control:** Efficient code management with Git and GitHub.

---

## Let's Connect! 🤝

I'm always open to new connections, opportunities, and challenges. Feel free to reach out!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-palma-sanches-dev)
[![E-mail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lucaspalma331@gmail.com)
