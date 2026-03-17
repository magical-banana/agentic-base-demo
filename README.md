# 🍌 Magical Banana | Self-Evolving Portfolio

This repository is an experiment in **Agentic DevOps**. It is a self-coding portfolio site where a **FreeTierAI-powered AI Agent (Aider)** manages the codebase, architecture, and deployment based on GitHub Issues.

## ⚙️ The Loop
1.  **Input:** User opens a GitHub Issue or comments on one.
2.  **Trigger:** GitHub Actions workflow kicks off.
3.  **Context:** The agent reads the `.agents/senior-developer.md` persona and the `memory-bank/` for state management.
4.  **Execution:** Aider applies changes to the HTML/CSS using a 20-request daily quota limit.
5.  **Persistence:** The agent updates `activeContext.md` to ensure state is maintained across runs.

## 🏗️ Architecture
- **Infrastructure:** GitHub Actions (Ubuntu-latest).
- **AI Orchestrator:** [Aider](https://aider.chat/) + LiteLLM.
- **Model:** `gemini-3-flash` (Free Tier).
- **Design System:** Tailwind CSS (CDN) + Lucide Icons.
- **State Management:** Custom "Memory Bank" (`memory-bank/` folder).

## 🛠️ Usage for magical-banana
To change the site, simply open an issue with your request.    
Wait for the agent to generate the code and create the PR.    
Once the PR is reviewed and approved to the main branch, the deployment is triggered automatically.    
Visit the website at https://magical-banana.github.io/agentic-base-demo/ 