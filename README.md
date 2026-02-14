## Pitch
*  **Prompt Injection Detection: Uses a semantic classifier to detect "jailbreak" patterns (e.g., DAN, Role-play, and Ignore-Instruction attacks).**

*  **Automated PII Redaction: A custom pipeline that identifies and masks South African ID numbers, phone numbers, and bank account details before they hit the LLM.**

*  **Adversarial Robustness Testing: Includes a suite of automated "red-teaming" scripts using Garak to simulate model exploitation.**

*  **POPIA Compliance Audit Log: Generates a secure JSON log of blocked malicious attempts for regulatory reporting.**

## Tech Stack
* **Engine:** Python, LangChain, OpenAI/Ollama
* **Security:** Microsoft Presidio (Anonymization), Vigil-LLM (Scanners)
* **Deployment:** Docker, Streamlit (Demo UI)
