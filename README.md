🤖 YES Ai: The Next-Generation Multi-Tool AI Agent
An advanced framework powered by Google Gemini for high-impact decision-making and seamless automation. Designed for serverless deployment and massive scalability on Google Cloud.

## 🌟 Core Features
Our agent combines multiple tools to deliver smart, accurate, and multi-lingual responses.

| Icon | Feature | Description |
| :---: | :--- | :--- |
| 🔍 | **Deep Research Mode** | Fetches, synthesizes, and summarizes multi-source information on any real-world topic using external search APIs. |
| 🌐 | **Smart Chat** | Supports fluid conversation and complex queries in **English, Bengali, and Hindi**. |
| 🧮 | **Math Solver & News** | Utilizes internal tools to handle calculations and provides the latest news headlines. |
| ☁️ | **Real-Time Weather** | Provides up-to-the-minute, location-based weather updates using external APIs. |
| 🔒 | **Secure Login & Auth** | Custom login system implemented with email OTP verification and secure password hashing (bcrypt). |

---

## 💡 Future Scope & Technical Insight (Hybrid V2)
*(This section outlines our vision for advanced deployment strategies, showcasing deep technical planning for the judges.)*

| Area | Current Status (Challenge Submission) | Planned Upgrade (Hybrid V2) | Impact on Users |
| :--- | :--- | :--- | :--- |
| **Model Architecture** | Pure gemini-2.0-flash | **Hybrid Model Integration (Gemini + Llama 3)** | Optimized cost-effectiveness and specialized custom response tones. |
| **I/O Capabilities** | Text input/output only. | **🔊 Voice Commands & TTS** | Implementing Speech-to-Text for input and Text-to-Speech for output for better accessibility and interaction. |
| **Generative Tools** | Search, Math, Weather tools. | **🖼️ Photo Generation Integration** | Adding a feature to generate photorealistic images directly within the chat for visual creativity. |

---

## 🛠 Tech Stack
- **AI Core:** Google gemini-2.0-flash
- **Frontend/Backend:** Python / Streamlit
- **Authentication:** Custom Login System (bcrypt, Email OTP)
- **Deployment:** Streamlit Cloud

---

## 🔗 Live Demo & Setup

| Resource | Link |
| :--- | :--- |
| **Live Demo URL** | https://yesai2-ranajitdhar.streamlit.app |
| **GitHub Repository** | https://github.com/ranajitdharpersonal/YES-Ai-2.0-Multi-Tool.git |

### 💻 Local Setup Instructions

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ranajitdharpersonal/YES-Ai-2.0-Multi-Tool.git](https://github.com/ranajitdharpersonal/YES-Ai-2.0-Multi-Tool.git)
    cd YES-Ai-2.0-Multi-Tool
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Set up Secrets:** Create a `secrets.toml` file with all necessary API keys (GEMINI_API_KEY, OPENWEATHER_API_KEY, etc.).

4.  **Run the app:**
    ```bash
    streamlit run app.py
    ```
