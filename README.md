# Spring AI JDBC Chat Memory - PostgreSQL
This repository demonstrates how to use **Spring AI's JDBC Chat Memory** with **PostgreSQL** to manage chat conversations persistently and reliably.

🚀 **It covers two key use cases**:
- A shared chat memory for all users (using a common conversation ID).
- A user-specific chat memory where each conversation history is isolated.

📖 **Dive Deeper**: For a complete walkthrough and detailed explanation, read our blog:  
👉 [Spring AI JDBC Chat Memory: Building Persistent Conversational Applications with PostgreSQL and MariaDB](https://bootcamptoprod.com/spring-ai-jdbc-chat-memory-guide/)

---

## 📦 Environment Variables

Make sure to provide these Java environment variables when running the application:

- `GEMINI_APP_KEY`: Your Google Gemini API key.
- `DB_USERNAME`: Your PostgreSQL username.
- `DB_PASSWORD`: Your PostgreSQL password.

⚡ **Important:** Ensure that a database named `springai` exists in your PostgreSQL instance, or create one before running the application.