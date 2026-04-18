# 🛡️ Diligent ACE: Agentic Certification & Enablement
**An Applied AI Prototype for the Diligent Partner Academy** *Developed by Rhishi Ayyappan | MSc Computer Science (1st Class Honours), University of Galway*

---

## 🚀 Live Interactive Demo
**Don't just take my word for it—try the engine yourself.** The production prototype is live 24/7 on Hugging Face Spaces. Click the preview below to launch the dashboard.


<img width="812" height="711" alt="ui_preview" src="https://github.com/user-attachments/assets/faf072cf-63f4-40c3-906e-b991ad18a686" />

(https://huggingface.co/spaces/rhishikumarayyappan/Diligent-ACE-Engine)

> **💡 Pro-Tip for Reviewers:** Test the **Abstention Logic** by entering a vague status (e.g., *"Partner attended, score pending"*). Notice how the system prioritizes GRC integrity by flagging the case for human review instead of guessing.

---

## 📊 Executive Impact Summary
In a high-stakes GRC (Governance, Risk, and Compliance) environment, manual partner certification is an expensive bottleneck. **Diligent ACE** leverages stateful AI to automate this process while maintaining 100% data integrity.

| Metric | Outcome |
| :--- | :--- |
| **OpEx Reduction** | Estimated **250+ manual hours saved** per year. |
| **Governance** | **Conservative Inference** (Abstention) ensures zero false-positives. |
| **Global Reach** | Native localization support for **Spanish & Portuguese** hubs. |
| **Latency** | **~2.09ms** inference-optimized retrieval. |

---

## 🧠 Systems Thinking: The Architecture
Unlike traditional chatbots, this engine is built as a **State Machine** using **LangGraph**. This ensures every certification journey is predictable, traceable, and auditable.

### **The Multi-Node Workflow**
1. **Retrieval (RAG):** Context-aware searching of Diligent Academy standards via **FAISS**.
2. **Conservative Evaluation:** A logic gate that calculates a Trust Score ($T$). If $T < 0.85$, the AI **abstains** and routes to a Human-in-the-Loop (HITL) node.
3. **Localization Engine:** Real-time translation of feedback to improve the global learner experience.
4. **Impact Node:** Records metadata for operational reporting and efficiency tracking.



---

## 🛠️ Technical Stack
* **Orchestration:** [LangGraph](https://github.com/langchain-ai/langgraph) (Stateful AI Agents)
* **Vector Store:** [FAISS](https://github.com/facebookresearch/faiss) (Semantic Search)
* **Model:** HuggingFace `all-MiniLM-L6-v2` (Performance Optimized)
* **Deployment:** Hugging Face Spaces + Gradio SDK
* **Framework:** LangChain & Python 3.12

---

## 📂 Repository Contents
* `app.py`: The production script powering the live Hugging Face deployment.
* `Diligent_ACE_Research.ipynb`: Detailed research notebook showing threshold calibration and RAG testing.
* `requirements.txt`: Environment configuration for zero-friction deployment.

---

